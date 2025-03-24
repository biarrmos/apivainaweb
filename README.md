# API Livros Doados Vai na Web

Essa é uma API simples feita com Flask e SQLite para fins de estudo na escola Vai Na Web. Ela permite cadastrar e listar os livros doados.

## Como rodar o projeto?

1. Faça o clone do repositório:
```bash
git clone <LINK_DO_REPOSITÓRIO>
cd nome_do_projeto
```

2. Crie um ambiente virtual (obrigatório)

**Windows**
```bash
python -m venv venv
source venv/Scripts/activate
```

**Linux/Mac**
```bash
python3 -m venv venv
source venv/bin/activate
```

3. Baixe as dependências:
```bash
pip install -r requirements.txt
```
4. Inicie o servidor:
```bash
python app.py
```

>A API estará disponível em http://127.0.0.1:5000/


## Endpoints

### POST/doar

Endpoint para cadastro das informações do livro doado.

**Envio em JSON**
```json
   {
   "titulo":"Ainda estou aqui",
    "categoria":"Drama",
    "autor":"MarceloRubens Paiva",
    "image_url":"https://..."
    }
```
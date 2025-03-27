### Estrutura de Pasta do Projeto:

```

├── app/
│   ├── __init__.py
│   ├── main.py            # Inicializa o FastAPI e importa os módulos
│   ├── models.py          # Definições dos modelos de dados (ORM)
│   ├── schemas.py         # Definições dos schemas (Pydantic)
│   ├── database.py        # Configuração do banco de dados e conexão
│   ├── api/
│   │   ├── __init__.py
│   │   ├── endpoints.py   # Endpoints da API (CRUD de produtos)
│   ├── core/
│   │   ├── __init__.py
│   │   └── config.py      # Configurações do sistema
│   ├── repository/
│   │   ├── __init__.py
│   │   └── product_repo.py # Repositório responsável pela manipulação dos dados
│   ├── service/
│   │   ├── __init__.py
│   │   └── product_service.py # Lógica de negócios para os produtos
├── requirements.txt       # Dependências
├── docker-compose.yml     # Configuração Docker
├── Dockerfile             # Dockerfile para o backend
└── tests/                 # Testes
    ├── __init__.py
    └── test_product.py    # Testes dos produtos

```

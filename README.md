### Pearson Regression App

Este repositório contém uma aplicação web construída com FastAPI que calcula a correlação de Pearson entre dois conjuntos de dados.

#### Funcionalidades

- Entrada de coordenadas `x` e `y`.
- Adição de pares de coordenadas a uma tabela.
- Cálculo da correlação de Pearson.
- Exibição de mensagens de erro para entradas inválidas.

#### Estrutura do Projeto

```
pearson-regression-app/
├── main.py
├── templates/
│   └── index.html
└── static/
    └── style.css
```

#### Como Executar

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/pearson-regression-app.git
   cd pearson-regression-app
   ```

2. Instale as dependências:
   ```sh
   pip install fastapi jinja2 uvicorn
   ```

3. Execute o servidor:
   ```sh
   uvicorn main:app --reload
   ```

4. Acesse a aplicação em `http://127.0.0.1:8000`.

#### Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

#### Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

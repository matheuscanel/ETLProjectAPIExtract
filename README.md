# ETL com Python usando Requests

Este é um projeto de **ETL (Extract, Transform, Load)** desenvolvido em Python, utilizando a biblioteca `requests` para coleta de dados de APIs RESTful. Ele foi criado para facilitar a automação do processo de coleta, transformação e armazenamento de dados.

---

## Funcionalidades

- **Extração de dados**: Realiza requisições para APIs ou endpoints REST utilizando a biblioteca `requests`.
- **Transformação de dados**: Processa, filtra e limpa os dados extraídos para atender aos requisitos do projeto.
- **Carregamento de dados**: Salva os dados transformados em bancos de dados, arquivos locais (CSV, JSON, etc.) ou sistemas de armazenamento.

---

## Tecnologias Utilizadas

- **Python 3.8+**
- **Bibliotecas principais**:
  - [`requests`](https://docs.python-requests.org/): Para fazer as requisições HTTP.
  - [`pandas`](https://pandas.pydata.org/): Para manipulação e transformação de dados.
  - [`json`](https://docs.python.org/3/library/json.html): Para lidar com dados estruturados em JSON.
  - [`sqlalchemy`](https://www.sqlalchemy.org/) (opcional): Para integração com bancos de dados.

---

## Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/etl-python-requests.git
   cd etl-python-requests

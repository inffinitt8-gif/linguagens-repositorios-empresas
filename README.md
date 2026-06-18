# linguagens-repositorios-empresas

Repositório contendo dados sobre as linguagens de programação utilizadas nos repositórios públicos de três grandes empresas de tecnologia: **Amazon**, **Netflix** e **Spotify**.

## Sobre os dados

Os dados foram coletados via [API pública do GitHub](https://api.github.com) e organizados em arquivos CSV com as seguintes colunas:

- `repository_name` — nome do repositório
- `language` — linguagem de programação principal utilizada

## Arquivos

| Arquivo | Empresa | Repositórios |
|---|---|---|
| `linguagens_amzn.csv` | Amazon (amzn) | 169 |
| `linguagens_netflix.csv` | Netflix | 234 |
| `linguagens_spotify.csv` | Spotify | 284 |

## Como os dados foram gerados

Os dados foram extraídos com Python utilizando a biblioteca `requests` para consumir a API do GitHub, e a biblioteca `pandas` para estruturar e exportar os dados em formato CSV.

## Tecnologias utilizadas

- Python 3.10
- requests
- pandas
- API REST do GitHub

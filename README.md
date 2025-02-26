# Análise e Visualização de Dados - IMDB Movies

## Sobre o Projeto

Este projeto tem como objetivo realizar uma análise exploratória dos dados do dataset **IMDB Movies**, identificando padrões, correlações e retirando possíveis insights sobre os filmes mais bem avaliados e suas características.

## Dataset

O dataset utilizado foi obtido no Kaggle e contém informações sobre os 1000 filmes e séries mais bem avaliados do IMDB. Ele inclui atributos como:

- Nome do filme
- Ano de lançamento
- Duração
- Gênero
- Nota no IMDB
- Diretor e elenco principal
- Receita bruta
- Número de votos, entre outros.

[Link para o dataset](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows/data)

## Tecnologias Utilizadas

- **Python** (para análise de dados e visualização)
- **Pandas** (para manipulação de dados)
- **Matplotlib e Seaborn** (para geração de gráficos e visualização de dados)
- **Streamlit** (para criar uma interface interativa)

## Funcionalidades

A aplicação permite:

- Filtrar os dados por colunas específicas.
- Visualizar estatísticas descritivas do dataset.
- Analisar dados faltantes.
- Gerar visualizações interativas sobre:
  - Relação entre nota IMDB e receita bruta.
  - Correlação entre duração dos filmes e sua nota.
  - Evolução do número de votos ao longo dos anos.
  - Distribuição de filmes por gênero.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute a aplicação Streamlit:
   ```bash
   streamlit run main.py
   ```

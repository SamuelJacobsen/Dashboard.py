# Dashboard.py - Aprendendo a criar um dashboard com Python

Este script, chamado Dashboard.py, foi desenvolvido para criar um dashboard interativo utilizando Python. O dashboard possui as seguintes funcionalidades:

## Funcionalidades:

- Importação das bibliotecas necessárias (`streamlit`, `pandas`, `plotly.express`).
- Configuração da página do Streamlit para um layout amplo.
- Leitura de um arquivo CSV chamado "arq.csv" utilizando o Pandas.
- Conversão da coluna "Date" para o formato de data.
- Adição de uma coluna "Month" para filtragem por mês.
- Criação de um seletor na barra lateral para escolher o mês desejado.
- Filtragem dos dados com base no mês selecionado.
- Utilização do Plotly Express para criar e exibir gráficos em um layout de colunas.

## Gráficos incluídos:

- Faturamento por dia em forma de barras.
- Faturamento por tipo de produto em barras.
- Faturamento por filial em barras.
- Gráfico de pizza para exibir os tipos de pagamento.
- Avaliação por filial em forma de barras.

## Instruções para Execução:

Para executar este dashboard, siga os seguintes passos:

1. Instale as dependências necessárias utilizando o comando: `pip install streamlit pandas plotly`.
2. Inicie o servidor usando o comando: `streamlit run Dashboard.py`.

# Análise de Entrega de Produtos no Google Colab

Este projeto utiliza o Google Colab para analisar os dados de entregas de produtos de uma determinada empresa.
E algumas perguntas foram feitas de acordo com a base de dados fornecida para facilitar a análise em si. E algumas dessas perguntas são:

 - Qual é o total de faturamento?
 - Qual é a quantidade de motoristas?
 - Qual é a quantidade de devolução dos produtos por Motorista?
 - Qual a quantidade de devolução dos produtos ?
 - Quais são os motivos de devolução dos produtos por Motorista?
 - Mapear quantos produtos foram entregues fora do prazo.
 - Quais motoristas atrasam mais a entrega dos produtos?

Com isso, o objetivo deste projeto é verificar insights para auxiliar o Gestor da empresa a tomar uma decisão acertiva, 
baseada em análise de dados.

## Descrição

O projeto está dividido em:
- Analisar e transformar os dados com código Python e suas bibliotecas; e
- Visualizações das respostas em formato de tabelo e gráfico.

## Tecnologias

- Google Colab
- Python
- Pandas
- Matplotlib
- Seaborn

## Como Rodar o Projeto no Google Colab

1. **Abrir o Notebook no Google Colab**: Clique no link abaixo para abrir o notebook diretamente no Google Colab:
   [Abrir no Google Colab][(https://colab.research.google.com/drive/1Q5VppeAhTqz1sqq732usRLHuRdTlovV2)]

2. **Carregar os Dados**: Se o projeto incluir dados locais, faça upload dos arquivos necessários para o Colab usando o comando `files.upload()` ou conecte-se a um repositório no Google Drive.

   ```python
   from google.colab import files
   uploaded = files.upload()


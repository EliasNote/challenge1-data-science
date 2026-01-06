# Desafio Oracle ONE — Alura Store Brasil

## Sobre o projeto

Este projeto tem como objetivo ajudar o Senhor João a decidir qual loja da rede Alura Store vender para iniciar um novo empreendimento. Foram analisados dados de vendas, desempenho e avaliações das 4 lojas fictícias, utilizando Python, Pandas, Matplotlib e Seaborn.

## Estrutura

- `AluraStoreBrasil.ipynb`: Notebook com toda a análise, gráficos e conclusão.
- `base-de-dados-challenge-1/`: Pasta com os arquivos de dados (CSV) das lojas:
  - loja_1.csv
  - loja_2.csv
  - loja_3.csv
  - loja_4.csv

## Principais análises realizadas

- **Faturamento total por loja**: Soma dos preços das vendas de cada loja.
- **Vendas por categoria de produto**: Contagem de vendas por categoria em cada loja.
- **Média de avaliação dos clientes**: Cálculo da média das avaliações das compras por loja.
- **Produtos mais e menos vendidos**: Identificação dos 5 produtos mais e menos vendidos por loja.
- **Frete médio por loja**: Cálculo do valor médio do frete em cada loja.

## Visualizações

- Gráfico de barras do faturamento total por loja.
- Heatmap das vendas por categoria de produto por loja.
- Gráfico de linha do frete médio por loja.

## Como executar

1. Crie um ambiente virtual (opcional):
   ```
   python -m venv venv
   .\venv\Scripts\activate
   ```
2. Instale as dependências:
   ```
   pip install pandas matplotlib seaborn jupyter
   ```
3. Abra o notebook:
   ```
   jupyter notebook
   ```
4. Execute o arquivo `AluraStoreBrasil.ipynb`.

> Os dados podem ser carregados dos arquivos locais em `base-de-dados-challenge-1/`.

## Conclusão e recomendação

Após as análises, conclui-se que a loja recomendada para venda é a **Loja 4**. Apesar de possuir o menor frete médio, isso não se refletiu em maior faturamento ou destaque nas vendas por categoria. A Loja 4 apresentou o pior desempenho financeiro entre as quatro lojas, sendo a escolha mais adequada para venda segundo os dados analisados.

---

Bom projeto! 🚀

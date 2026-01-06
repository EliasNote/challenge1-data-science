# 🚀 Desafio Oracle ONE — Alura Store Brasil

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?logo=matplotlib)

---

## 👨‍💼 Sobre o projeto

Este projeto tem como objetivo ajudar o Senhor João a decidir qual loja da rede Alura Store vender para iniciar um novo empreendimento. Foram analisados dados de vendas, desempenho e avaliações das 4 lojas fictícias, utilizando **Python**, **Pandas**, **Matplotlib** e **Seaborn**.

---

## 📁 Estrutura

```
challenge1-data-science/
├── AluraStoreBrasil.ipynb
└── base-de-dados-challenge-1/
    ├── loja_1.csv
    ├── loja_2.csv
    ├── loja_3.csv
    └── loja_4.csv
```

---

## 📊 Principais análises realizadas

| Métrica                         | Descrição                                     |
| ------------------------------- | --------------------------------------------- |
| 💰 Faturamento total por loja   | Soma dos preços das vendas de cada loja       |
| 📦 Vendas por categoria         | Contagem de vendas por categoria em cada loja |
| ⭐ Média de avaliação           | Média das avaliações das compras por loja     |
| 🏆 Produtos mais/menos vendidos | Top 5 e bottom 5 produtos por loja            |
| 🚚 Frete médio por loja         | Valor médio do frete em cada loja             |

---

## 🎨 Visualizações

- 📊 **Gráfico de barras** do faturamento total por loja
- 🟪 **Heatmap** das vendas por categoria de produto por loja
- 📈 **Gráfico de linha** do frete médio por loja

<img src="https://user-images.githubusercontent.com/6748242/235352839-2e2e7e7e-2e7e-4e7e-8e7e-2e7e7e7e7e7e.png" alt="Exemplo de gráfico de barras" width="400"/>

---

## ⚙️ Como executar

1. Crie um ambiente virtual (opcional):
   ```bash
   python -m venv venv
   .\venv\Scripts\activate
   ```
2. Instale as dependências:
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```
3. Abra o notebook:
   ```bash
   jupyter notebook
   ```
4. Execute o arquivo `AluraStoreBrasil.ipynb`.

> Os dados podem ser carregados dos arquivos locais em `base-de-dados-challenge-1/`.

---

## 📝 Conclusão e recomendação

Após as análises, conclui-se que a loja recomendada para venda é a **Loja 4**. Apesar de possuir o menor frete médio, isso não se refletiu em maior faturamento ou destaque nas vendas por categoria. A Loja 4 apresentou o pior desempenho financeiro entre as quatro lojas, sendo a escolha mais adequada para venda segundo os dados analisados.

---

<p align="center"><b>Bom projeto! 🚀</b></p>

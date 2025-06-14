
<img src="assets/retail-banner.png" alt="Retail Forecast Banner" style="width:100%; max-height:180px;" />

#  Previsão de Demanda em Lojas de Varejo com Aprendizado de Máquina

##  Descrição do Projeto

Este projeto tem como objetivo aplicar técnicas de aprendizado de máquina para prever a demanda de produtos em lojas de varejo com base em informações históricas de estoque, promoções, preço e características sazonais. A proposta consiste em construir um modelo preditivo de regressão capaz de estimar com mais precisão a quantidade de produtos a ser requisitada por loja, otimizando o planejamento de reposição e reduzindo custos operacionais.

##  Objetivo

Prever a variável `Demand`, que representa a demanda futura de um produto, com base em:

- Loja (`Store_ID`)
- Produto (`Product_ID`, `Category`)
- Data (`Date`, `Season`)
- Preço (`Price`, `Discount`, `Competitor_Price`)
- Estoque atual (`Current_Stock`)
- Promoções (`Promotion`, `Is_Weekend`, `Holiday`)
- Clima (`Weather_Conditions`)
- Histórico de vendas (`Units_Sold`, `Units_Ordered`)

##  Tecnologias Utilizadas

- Python
- Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

##  Estrutura do Projeto

```
📦 retail-demand-forecast
├── main.ipynb           ← Notebook principal com pipeline completo
├── README.md            ← Este arquivo
├── data/                ← Dataset em CSV
├── assets/              ← Imagens e banners utilizados
└── .ipynb_checkpoints   ← Criado automaticamente pelo Jupyter
```

##  Como obter os dados

Este projeto utiliza o dataset **Retail Store Inventory and Demand Forecasting**, disponível gratuitamente no Kaggle.

### 🔗 Link:
[https://www.kaggle.com/datasets/atomicd/retail-store-inventory-and-demand-forecasting](https://www.kaggle.com/datasets/atomicd/retail-store-inventory-and-demand-forecasting)

###  Instruções:

1. Crie uma conta no Kaggle, se ainda não tiver.
2. Acesse o link da competição e clique em “Download”.
3. Extraia o arquivo `retail_dataset.csv` (ou equivalente) para a pasta `data/` do projeto.

##  Pipeline do Projeto

1. Introdução e objetivo
2. Sobre os dados
3. Importação das bibliotecas
4. Carregamento e análise exploratória (EDA)
5. Pré-processamento dos dados
6. Modelagem preditiva (regressão)
7. Avaliação dos modelos
8. Conclusão e considerações finais

---

*Desenvolvido por [Smaley Marques]* – 2025

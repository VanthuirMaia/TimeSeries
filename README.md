# TimeSeries

Repositório de estudos práticos em séries temporais com foco em previsão de demanda, desenvolvido em paralelo com a leitura do livro _Forecasting: Principles and Practice (Pythonic Way)_.

## Objetivo

Praticar conceitos de séries temporais aplicando-os em datasets reais, evoluindo da exploração básica até modelos de previsão hierárquica.

## Estrutura

```
time-series/
├── 01-store-sales/        # Previsão de vendas - Kaggle Store Sales
├── 02-combustivel/        # Consumo de combustível - dados do PitBox (em breve)
├── 03-gestto/             # Demanda de agendamentos - Gestto (em breve)
└── README.md
```

> Os dados brutos não estão versionados. Cada projeto tem instruções de onde obtê-los.

## Projetos

### 01 - Store Sales (Kaggle)

Dataset da competição [Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting).

- 54 lojas, 33 famílias de produto, 4 anos de dados (2013-2017)
- Estrutura hierárquica: rede > loja > família de produto
- Análise exploratória: tendência de crescimento e sazonalidade semanal identificadas

**Para rodar:**

1. Baixa os dados em kaggle.com/competitions/store-sales-time-series-forecasting
2. Cola na pasta `01-store-sales/data/`
3. Ativa a venv e roda os notebooks em ordem

## Stack

- Python 3.12
- pandas, matplotlib, seaborn, plotly
- statsmodels, scikit-learn

## Como usar

```bash
python -m venv .venv
.venv\Scripts\activate        # Windows
pip install pandas matplotlib seaborn plotly statsmodels scikit-learn
```

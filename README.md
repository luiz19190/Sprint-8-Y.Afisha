# Sprint 8 — Y.Afisha Marketing Analysis

Projeto de análise de marketing desenvolvido no curso **TripleTen Data Analyst**.

## Objetivo

Atuar como estagiário no departamento analítico da Y.Afisha e ajudar a empresa a otimizar despesas com marketing, respondendo três perguntas centrais:

- Como os clientes usam o produto?
- Quando eles começam a comprar?
- Quanto dinheiro cada origem de tráfego gera em relação ao que é investido?

## Período analisado

Janeiro/2017 a Dezembro/2018

## Datasets

| Arquivo | Descrição |
|---------|-----------|
| `visits_log_us.csv` | Sessões de usuários (uid, device, source_id, timestamps) |
| `orders_log_us.csv` | Pedidos realizados (uid, buy_ts, revenue) |
| `costs_us.csv` | Gastos de marketing por origem e data |

Os CSVs não estão no repositório (o de visitas tem 25 MB). Para rodar o notebook, baixe os três arquivos públicos da TripleTen para a pasta `data/`:

```bash
mkdir data
curl -o data/visits_log_us.csv https://code.s3.yandex.net/datasets/visits_log_us.csv
curl -o data/orders_log_us.csv https://code.s3.yandex.net/datasets/orders_log_us.csv
curl -o data/costs_us.csv https://code.s3.yandex.net/datasets/costs_us.csv
```

## Métricas analisadas

- **Produto:** DAU, WAU, MAU, Sticky Factor, retenção por coorte, ASL
- **Vendas:** conversão, pedidos por cliente, ticket médio, LTV por coorte
- **Marketing:** gastos por origem, CAC, ROMI acumulado por origem e age, comparativo por dispositivo

## Tecnologias

Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

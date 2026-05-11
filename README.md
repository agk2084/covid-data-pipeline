# COVID Data Pipeline

Projeto de análise de dados da COVID-19 utilizando Python, SQL e Power BI.

## Estrutura do Projeto

```text
covid-data-pipeline/
├── data/
│   ├── final/
│   ├── processed/
│   └── raw/
├── sql/
│   ├── create_tables.sql
│   ├── queries.sql
│   └── transformations.sql
├── src/
│   ├── extract.py
│   ├── load.py
│   ├── pipeline.py
│   └── transform.py
├── .gitignore
├── README.md
└── requirements.txt
```

## Objetivo

Criar um pipeline ETL para extração, transformação e análise de dados públicos da COVID-19.

## Tecnologias

- Python
- Pandas
- SQL
- SQLite
- Power BI

## Estrutura do projeto

- data/: dados brutos e tratados
- scripts/: scripts ETL
- sql/: consultas SQL
- dashboard/: dashboards Power BI
- notebooks/: análises exploratórias

## Etapas do projeto

Fonte de Dados
      ↓
Extract (Python)
      ↓
Raw Data
      ↓
Transform (SQL/Pandas)
      ↓
Banco de Dados
      ↓
Consultas SQL
      ↓
Dashboard/Análises

## Etapas

| Etapa                       | Objetivo                              | O que pesquisar                                                           | Resultado esperado                    |
| --------------------------- | ------------------------------------- | ------------------------------------------------------------------------- | ------------------------------------- |
| 1. Entender ETL             | Compreender o fluxo de dados          | ETL, ELT, pipeline de dados, engenharia de dados                          | Entender Extract → Transform → Load   |
| 2. Git e GitHub             | Organizar o projeto profissionalmente | `git init`, `git add`, `git commit`, `git push`, README, `.gitignore`     | Criar e manter repositório organizado |
| 3. Ambiente Python          | Preparar ambiente de desenvolvimento  | `venv`, `pip`, `requirements.txt`                                         | Ambiente virtual funcionando          |
| 4. Extração de Dados        | Coletar dados reais                   | `pandas.read_csv`, APIs, `requests`                                       | Baixar e abrir datasets               |
| 5. Análise Exploratória     | Entender os dados                     | `isnull()`, `describe()`, `duplicated()`                                  | Identificar problemas nos dados       |
| 6. Limpeza e Transformação  | Tratar os dados                       | SQL (`SELECT`, `WHERE`, `GROUP BY`, `CASE`) e Pandas (`dropna`, `fillna`) | Dados limpos e padronizados           |
| 7. Banco de Dados           | Armazenar dados corretamente          | PostgreSQL, pgAdmin, `CREATE TABLE`, `INSERT`                             | Banco configurado                     |
| 8. Load                     | Enviar dados para o banco             | SQLAlchemy, `to_sql()`                                                    | Pipeline ETL funcionando              |
| 9. Consultas Analíticas     | Gerar insights                        | CTEs, Window Functions, agregações                                        | Consultas e análises SQL              |
| 10. Dashboard               | Visualizar dados                      | Power BI, KPIs, gráficos                                                  | Dashboard conectado ao banco          |
| 11. Melhorias Profissionais | Evoluir o projeto                     | Docker, Airflow, logs, testes, GitHub Actions                             | Projeto mais próximo do mercado       |

## Ordem de aprendizado

1. Git/GitHub
2. Python básico
3. Pandas
4. SQL
5. PostgreSQL
6. ETL
7. Dashboard
8. Docker/Airflow



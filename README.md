# Sales Analytics Pipeline

## Goal
A cloud-ready, modular ETL pipeline for sales analytics with a dashboard for business insights.

## Tech Stack
- Python
- Apache Airflow
- DuckDB (local)
- Streamlit
- GitHub Actions (CI/CD)
- Pandas & SQL

## Folder Structure
sales-analytics-pipeline/
│
├── dags/ # Airflow DAG definitions
├── etl/ # ETL helper scripts, SQL configs
├── data/raw/ # Raw CSV/API data dumps
├── data/processed/ # Cleaned data
├── warehouse/ # DuckDB database
├── dashboard/ # Streamlit app
├── .github/workflows/ # CI/CD configs
└── docs/ # Docs & diagrams

markdown
Copy
Edit

## How to Run Locally
1. Clone the repo.
2. Place raw sales CSV in `data/raw/`.
3. Run ETL script: `python etl/run_etl.py`.
4. Launch dashboard: `streamlit run dashboard/app.py`.

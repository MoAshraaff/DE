# Lab 3 – Cleaning the NYC Yellow Taxi data (Jan 2021)

INF4058 Data Engineering. Profiling and cleaning only; the cleaned data is **not** loaded into Postgres.

## Run
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
mkdir -p data
wget -P data https://github.com/DataTalksClub/nyc-tlc-data/releases/download/yellow/yellow_tripdata_2021-01.csv.gz
jupyter notebook lab3_cleaning.ipynb
```

## Contents
- `lab3_cleaning.ipynb` – look, chunked profiling, problem counts, decisions, `clean(df)` and checks.

Data files and `.venv` are not committed (see `.gitignore`).

# AI Job Market Analysis

An applied Pandas project exploring AI job roles, salaries, locations, remote work, and skill demand.

## Current checkpoint

Checkpoint 1 uses the first two Kaggle Pandas lessons:

- load and inspect a CSV file;
- select columns with `[]` and `.loc`;
- filter rows with Boolean conditions;
- record three early observations.

Open `notebooks/01_data_loading_and_selection.ipynb` in JupyterLab to begin.

## Dataset

The local source file is `ai_jobs_market_2025_2026.csv` from Kaggle. It contains 1,500 rows and 25 columns. The raw CSV is excluded from Git so the repository records analysis code rather than republishing the dataset.

## Project structure

```text
Self_Study/
|-- README.md
|-- ai_jobs_market_2025_2026.csv
|-- notebooks/
|   `-- 01_data_loading_and_selection.ipynb
|-- src/
|   `-- .gitkeep
|-- .gitignore
`-- requirements.txt
```

## Run locally

```powershell
python -m pip install -r requirements.txt
jupyter lab
```


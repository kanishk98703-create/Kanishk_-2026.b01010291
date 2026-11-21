# Climate Change Data Analysis

A Python-based analysis of climate data from 20 locations over 2024–2025, using Pandas, NumPy, and Matplotlib.

## Project Structure
```text
Climate_Change_Analysis_Project/
├── data/
│   ├── raw/             # Put climate_change_new1.csv here
│   └── processed/       # Notebook export goes here
├── images/              # Charts extracted from the notebook outputs
├── notebooks/
│   └── climate_change_analysis.ipynb
├── scripts/
├── requirements.txt
├── .gitignore
└── README.md
```

## Dataset
The notebook expects `data/raw/climate_change_new1.csv`. The source dataset was not included among the uploaded files, so add it before running the notebook. The notebook describes 240 records from 20 locations for 2024–2025.

## Run
1. Install Python.
2. Install dependencies: `pip install -r requirements.txt`
3. Add `climate_change_new1.csv` to `data/raw/`.
4. From the project root, start Jupyter: `jupyter notebook`
5. Open `notebooks/climate_change_analysis.ipynb` and run the cells.

## Project Sections
Data loading and inspection, missing values and extreme weather records, humidity and wind-speed cleaning, validation, exploratory visualisation, findings, conclusions, and exporting the cleaned dataset.

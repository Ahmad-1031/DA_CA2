# Predicting Self-Reported Diabetes Status Using Health and Lifestyle Indicators


| | |
|---|---|
| **Module** | DBMS71008 – Data Analytics |
| **Assignment** | CA2 – CRISP-DM Individual Project |
| **Student** | Ahmad Shahzad – T00269209 |
| **Academic Year** | 2026/27 |
| **Submission Deadline** | 4 December 2026 |


## Project Overview

This project investigates whether demographic characteristics, lifestyle behaviours and health indicators can be used to predict self-reported diabetes status.

The analysis follows the six phases of the Cross-Industry Standard Process for Data Mining (CRISP-DM) methodology and uses Python and machine learning techniques.

## Research Question

To what extent can demographic characteristics, lifestyle behaviours and health indicators predict whether an individual reports having diabetes?


## Dataset

The project uses the **CDC Behavioral Risk Factor Surveillance System (BRFSS) 2015 Diabetes Health Indicators** dataset, obtained from Kaggle.

The selected dataset contains:

- 253,680 survey records
- 21 predictor variables
- One binary target variable: `Diabetes_binary`

The target variable represents reported diabetes status:

- `0` – No reported diabetes
- `1` – Reported diabetes

The dataset contains self-reported survey information rather than independently verified clinical diagnoses.

**Dataset Source:** [Diabetes Health Indicators Dataset – Kaggle](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)


## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Visual Studio Code
- Git and GitHub



## Repository Structure

```text
Project/
│
├── Data/
│   ├── Raw/
│   │   └── diabetes_binary_health_indicators_BRFSS2015.csv
│   └── Processed/
│
├── Notebooks/
│   └── diabetes_crisp_dm_analysis.ipynb
│
├── Paper/
│   └── .gitkeep
│
├── References/
│   └── labs/
│       ├── Lab01_intro_to_pandas.ipynb
│       ├── Lab02_exploratory_data_analysis.ipynb
│       ├── Lab03_CRISP-DM Data Preparation.ipynb
│       ├── Lab04_Regression.ipynb
│       ├── Lab05_Logistic_Regression_and_Classification.ipynb
│       └── Lab06_Random_Forest.ipynb
│
└── README.md
```


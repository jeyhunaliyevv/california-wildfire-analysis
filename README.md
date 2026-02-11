# Fire Damage Detection and Analysis (California Wildfire)

## Overview
This project analyzes geographical and structural features of buildings affected by wildfires and builds a baseline machine learning model to predict fire damage status.

## Dataset
The dataset includes location and building attributes (e.g., X/Y coordinates, building type, damage status).  
> Note: If the dataset cannot be shared publicly, please add a short note on how to obtain it.

## Approach
- Data loading and basic profiling
- Data cleaning (missing values, data types)
- Exploratory Data Analysis (EDA) and visualizations
- Encoding categorical variables
- Baseline modeling with **Random Forest**
- Model evaluation (train/test split)

## Results
- Model performance: **TBD** (add accuracy / F1 / ROC-AUC if available)
- Key insights: damage distribution by building type and location patterns

## Repository Structure
- `notebooks/` – analysis and modeling notebooks
- `data/` – dataset files (or instructions to download)
- `requirements.txt` – Python dependencies

## How to Run
```bash
git clone <REPO_URL>
cd <REPO_NAME>
pip install -r requirements.txt
jupyter notebook

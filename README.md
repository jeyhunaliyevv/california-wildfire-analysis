# 🔥 California Wildfire | Fire Damage Prediction

### Machine Learning & Geospatial Data Analysis

## Project Overview

This project explores wildfire-related building damage in California using exploratory data analysis and machine learning.

The objective is to identify patterns associated with structural damage and develop a predictive model that estimates fire damage risk based on geographical and building characteristics.

The project combines data preprocessing, feature engineering, geospatial analysis, and supervised machine learning.

## Dataset

The analysis uses a California wildfire damage dataset containing information about affected structures.

Key features include:
- Geographic coordinates (X/Y)
- Building and structural characteristics
- Building type
- Fire damage status and severity
- Location-based attributes

**Data Availability:** The original dataset is not currently included in this repository. The analysis notebook demonstrates the methodology and modeling workflow.

## Methodology

**1. Data Preprocessing**
- Data quality assessment and missing value handling
- Data type validation and transformation
- Categorical feature encoding
- Feature selection and preparation

**2. Exploratory Data Analysis**
- Distribution of wildfire damage across structures
- Comparison of damage patterns by building type
- Analysis of geographical damage patterns
- Visual exploration of relevant features

**3. Machine Learning**
- Random Forest classification
- Train/test data splitting
- Model training and prediction
- Evaluation using classification metrics

## Model Performance

The Random Forest model was evaluated on a held-out test dataset.

| Metric | Result |
|---|---|
| Algorithm | Random Forest |
| ROC-AUC | Approximately 0.91–0.93 (recalled) |
| Validation | Train/Test Split |
| Task | Fire Damage Classification |

*Note: The ROC-AUC range is based on previously observed results recalled by the project author. The exact score has not been independently reverified.*

## Key Insights

The analysis focuses on understanding how building characteristics and geographical patterns relate to wildfire damage.

The project demonstrates the application of machine learning to disaster-related data and the use of predictive analytics to support risk assessment.

## Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Random Forest
- Matplotlib & Seaborn
- Jupyter Notebook

## Repository Structure

- `notebooks/` — Data analysis and machine learning notebooks
- `data/` — Dataset directory, where available
- `requirements.txt` — Python dependencies, where provided

## Running the Project

Install the required Python libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the analysis notebook to explore the data processing, visualization, and modeling workflow.

**Note:** Running the complete analysis requires access to the original dataset and updating its local file path.

---

**Project Category:** Machine Learning | Predictive Analytics | Geospatial Analysis

**Author:** Jeyhun Aliyev

**Professional Focus:** Data Scientist | AI/ML Engineer

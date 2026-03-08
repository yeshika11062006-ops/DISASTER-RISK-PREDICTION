# Disaster Risk Prediction using AI/ML

## Project Goal
Predict high-risk regions for natural disasters using historical global disaster data. Includes data preprocessing, exploratory data analysis, and predictive modeling.

## Folder Structure
- `data/` : Raw and processed datasets
- `notebooks/` : Jupyter notebooks for each step
- `results/` : Visualizations saved as PNG

## Workflow
1. **Data Preprocessing** (`1_data_preprocessing.ipynb`)
   - Cleaned dataset, handled missing values, feature engineering
2. **EDA & Visualization** (`2_eda_visualization.ipynb`)
   - Visualized disaster counts, deaths, damages, trends, and correlations
3. **Predictive Modeling** (`3_predictive_modeling.ipynb`)
   - Feature encoding, target creation
   - Random Forest + Logistic Regression
   - Evaluation: Confusion matrix, Classification report, ROC-AUC
   - Feature importance visualization

## Libraries Used
- pandas, numpy, matplotlib, seaborn, scikit-learn

## How to Run
1. Clone the repo:
```bash
git clone <your-repo-url>

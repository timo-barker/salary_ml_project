# Salary Prediction for Data Professionals

## Overview
A machine learning project analyzing salary trends among data professionals using survey data from Brent Ozar's database professional salary surveys (2017-2025). This project explores various regression models to predict salaries based on factors like location, experience, and job roles.

## Project Structure
```
salary-ml-project/
├── data/
│   └── Data_Professional_Salary_Survey_Responses.xlsx
├── images/
│   ├── column_transformer.png
│   ├── animated_plot.gif
│   └── static_plot.png
├── salary_ml_project.ipynb
├── README.md
└── requirements.txt
```

## Key Features
- Data cleaning and preprocessing pipelines
- Feature importance analysis
- Comparison of 12 different regression models
- Interactive visualizations using Plotly
- Cross-validation with performance metrics

## Models Evaluated
- Linear Models: Linear, Ridge, Lasso, Elastic Net, Bayesian Ridge
- Ensemble Methods: Random Forest, Gradient Boosting, HistGradient Boosting
- Other Approaches: KNN, SVR, Decision Trees, Polynomial Regression

## Results
Best performing models:
1. HistGradientBoostingRegressor (R² ≈ 0.65)
2. RandomForestRegressor (R² ≈ 0.63)
3. GradientBoostingRegressor (R² ≈ 0.62)

## Requirements
```python
numpy
pandas
scikit-learn
matplotlib
seaborn
plotly
statsmodels
```

## Usage
1. Clone this repository: `git clone https://github.com/timo-barker/salary_ml_project.git`
2. Install required packages: `pip install -r requirements.txt`
3. Open `salary_ml_project.ipynb` in Jupyter
4. Follow the notebook sections:
   - Data loading and preprocessing
   - Exploratory data analysis
   - Model training and evaluation
   - Results visualization

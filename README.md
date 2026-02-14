### Project Title

Wage Prediction Capstone Project

**Author**

Michael Yaacoub

#### Executive summary

This project analyzes the key factors that influence individual wages using exploratory data analysis (EDA) and machine learning. The objective is to identify which demographic, educational, and occupational variables most strongly affect wage outcomes and to establish a baseline predictive model for future improvement.

#### Rationale

Why should anyone care about this question?

Wage inequality and income prediction are important in labor economics, workforce planning, and public policy. Understanding wage drivers can help employers improve compensation strategy, policymakers design targeted interventions, and individuals make informed career and education decisions.

#### Research Question

What are you trying to answer?

What features most strongly predict wages, and how accurately can we predict wages using a baseline machine learning model?

#### Data Sources

What data will you use to answer you question?

The dataset includes demographic, educational, and occupational features such as age, education level, occupation, hours worked per week, experience-related variables, and industry classification.

#### Methodology

What methods are you using to answer the question?

- Data cleaning (duplicates, missing values, encoding, scaling)
- Feature engineering (experience proxy, grouped sparse categories, log-transformed wages)
- Exploratory data analysis (distribution checks, correlation matrix, boxplots, scatterplots, outlier review)
- Baseline modeling with a Voting Regressor ensemble of Linear Regression, Random Forest Regressor, and Gradient Boosting Regressor
- Performance evaluation using R², MAE, and RMSE

#### Results

What did your research find?

- Wages are right-skewed and become more symmetric after log transformation.
- Education level has a strong positive relationship with wages.
- Experience effects are nonlinear with diminishing returns.
- Tree-based models capture nonlinear relationships better than linear regression alone.
- Ensemble modeling improved baseline performance and predictive stability.
- Education, experience proxy, occupation category, and hours worked were among the most important features.

#### Next steps

What suggestions do you have for next steps?

- Perform hyperparameter tuning
- Evaluate additional models (e.g., XGBoost, regularized regression)
- Improve feature engineering
- Assess model fairness and bias
- Build stakeholder-friendly visualizations

#### Outline of project

- [Link to notebook 1](EDA_Data_Cleaning_Notebook.ipynb)
- [Link to notebook 2](Feature_Engineering_Notebook.ipynb)
- [Link to notebook 3](Baseline_Modeling_Notebook.ipynb)

##### Contact and Further Information

For questions or collaboration opportunities, please contact:
Michael Yaacoub
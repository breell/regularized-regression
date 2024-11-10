# Case Study Regression Python - Boston Housing Data

This repository contains a case study for implementing regression models in Python, specifically focusing on regularized regression techniques such as Ridge and Lasso. The case study aims to predict house prices in Boston using a dataset with various housing features.

## Project Objectives
1. Split the dataset for training, validation, and testing.
2. Visualize correlations and perform feature selection to handle redundant features.
3. Implement Ridge and Lasso regression models.
4. Conduct model evaluation to determine the best model.
5. Document the entire process, including feature selection, model training, and evaluation.

The dataset is based on the Boston Housing Data and includes the following features:
- Criminal rate (`crim`)
- Residential land zoned proportion (`zn`)
- Non-retail business acres proportion (`indus`)
- Is bounds with river (`chas`)
- Nitrogen oxides concentration (`nox`)
- Number rooms average (`rm`)
- Owner age proportion (`age`)
- Weighted distance to cities (`dis`)
- Accessibility index (`rad`)
- Tax rate (`tax`)
- Pupil-teacher ratio (`ptratio`)
- Black proportion (`black`)
- Percent lower status (`lstat`)

The target variable is `medv`, which represents the median house price.

## Workflow
1. **Data Preparation**: Split data into training, validation, and testing sets.
2. **Feature Selection**: Generate a correlation plot and select features to reduce multicollinearity.
3. **Model Training**:
   - Train Ridge and Lasso regression models with varying lambda values (`[0.01, 0.1, 1, 10]`).
   - Choose the best lambda using RMSE on the validation set.
4. **Model Interpretation**: Interpret model coefficients for insights.
5. **Evaluation**: Evaluate the best model on the test set using MAE, MAPE, and RMSE metrics.

## Tools Used
- **Python**
- **Visual Studio Code**

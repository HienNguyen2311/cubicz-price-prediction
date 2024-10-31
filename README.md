# Cubic Zirconia Price Prediction and Analysis
This project analyzes a dataset of cubic zirconia stones to predict prices and provide insights into which factors have the most significant impact on price. It uses linear regression and generalized additive models (GAM) to build predictive models and explore relationships between variables.
## Features
* Exploratory data analysis of cubic zirconia characteristics and prices
* Linear regression modeling
* Generalized additive modeling (GAM)
* Model assumption checking and diagnostics
* Feature selection and interaction analysis
* Price prediction using various methods: best subset selection with cross-validation, Ridge regression, LASSO regression
* Visualizations of relationships between variables
## Installation
1. Clone this repository
2. Install R and RStudio
3. Install required R packages:
```
install.packages(c("dplyr", "ggplot2", "pander", "psych", "car", "mgcv", "leaps", "glmnet"))
```
## Usage
1. Open the R project in RStudio
2. Run the R script
3. View generated plots and model outputs
## Data Source
Kaggle: https://www.kaggle.com/datasets/colearninglounge/gemstone-price-prediction
## Libraries Used
dplyr, ggplot2, psych, car, mgcv, leaps, glmnet
## Sample Visualizations
Scatterplot matrix

![project scatterplot matrix](https://github.com/user-attachments/assets/e50e07cc-a7b8-4b05-a7be-970cb50b6075)

Regression assumption check

![check regression assumptions plot before](https://github.com/user-attachments/assets/9fd0dc4d-2627-44e7-b695-cc663e89164b)

Resdiuals vs ppredictors

![project residuals vs predictos](https://github.com/user-attachments/assets/c48d0a33-3b38-4504-9333-c751777690e8)

## License
This project is licensed under the MIT License.

## Project Report
This project analyzes a dataset of cubic zirconia stones to predict prices and provide insights into which factors have the most significant impact on price. The report covers:
* Exploratory Data Analysis (EDA) of cubic zirconia characteristics and prices
* Linear regression modeling and assumption checking
* Generalized Additive Modeling (GAM)
* Feature selection and interaction analysis
* Model comparison using AIC, BIC, and Mallow's Cp
* Price prediction using various methods

Key findings include:
* Carat weight and length have the most significant impact on price
* There are non-linear relationships between some predictors and price
* Categorical variables (cut, color, clarity) show some counterintuitive relationships with price
* The GAM model outperformed the linear model in terms of fit
* Recommendations for which stone characteristics are likely to bring more revenue

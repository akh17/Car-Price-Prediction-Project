# Econometric Analysis of Car Pricing

## Overview
This project conducts an econometric analysis of a car dataset to estimate the relationship between various features (such as car length, width, curb weight, and engine size) and car pricing. The analysis employs statistical techniques, including transformations, to improve model fit and meet regression assumptions.

## Dataset
The dataset used in this analysis contains information on various cars, including features such as:
- Price
- Car Length
- Car Width
- Curb Weight
- Engine Size

Data source: [Car Data on Kaggle](https://www.kaggle.com/datasets/goyalshalini93/car-data)

## Analysis Steps
1. **Data Introduction**: Introduced the dataset and summarized its key features.
2. **Statistical Analysis**: Conducted descriptive statistics, histograms, quantile plots, and boxplots to visualize data distributions and identify outliers.
3. **Transformations**:
   - Explored and applied log transformations to stabilize variance and improve model fit.
   - Used residual plots and QQ plots to assess normality and homoscedasticity.
   - Performed Box-Cox analysis to determine the optimal transformation.
4. **Modeling**: Developed Ordinary Least Squares (OLS) regression models to analyze relationships between variables.
5. **Model Evaluation**: Assessed model performance using R-squared values and visualizations of residuals.

## Results
- Identified significant predictors of car pricing.
- Improved model fit and interpretation through transformations.
- Generated visualizations that support the findings, including scatterplots of transformed data.

## Technologies Used
- R
- R Markdown

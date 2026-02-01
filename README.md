# Asphalt Rut Depth Regression Analysis

This project implements a detailed regression analysis of asphalt rut depth data, inspired by Table 10.5-10.11 from Gorman and Toman. The analysis explores the relationships between rut depth and various asphalt properties such as viscosity, surface, base, run, fines, and voids. The project demonstrates both classical Ordinary Least Squares (OLS) regression and model selection techniques.

---

## Project Description

The dataset consists of 31 observations of asphalt samples with the following variables:

- y / rut_depth: Rut depth of the asphalt
- viscosity: Viscosity of the asphalt
- surface: Surface measurement
- base: Base measurement
- run: Run identifier
- fines: Fines content
- voids: Voids content

Key analyses performed in this project:

1. Data Exploration  
   - Table 10.5: Display the raw dataset
   - Log transformations of rut depth (`log_rut`) and viscosity (`log_visc`)

2. Regression Analysis 
   - Initial OLS regression model with all predictors
   - Calculation of variance inflation factors (VIFs)
   - Evaluation of model statistics: R², adjusted R², root MSE, coefficient of variation

3. Residual Analysis  
   - Normal probability plots
   - Residuals vs fitted values and predictors
   - Studentized residuals to identify influential observations

4. Model Selection 
   - All possible regressions using C(p) and adjusted R² methods
   - Forward, backward, and stepwise selection methods

5. Visualization  
   - Figures 10.12–10.27: Residual plots before and after log transformations

This project uses Python packages including `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, and `scipy`.

---

## How to Run

Provides OLS regression results for both original and log-transformed response variables.

Identifies significant predictors for asphalt rut depth.

Offers all-possible-regression analysis and model selection summaries.

Generates residual diagnostic plots for evaluating model assumptions.


## Author

Hacı Osman Budak

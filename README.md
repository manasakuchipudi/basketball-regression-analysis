# NBA Regression Analysis  
Analyzing NBA performance metrics and margin of victory (MOV) using R, multiple linear regression, and ANOVA  

## Project Overview
In this project, I analyzed NBA game data from the 2017–2019 seasons to better understand which team performance statistics are related to margin of victory. Using R, I explored the data, built and compared multiple regression models, and used ANOVA to test whether shooting percentages were significant predictors of game outcomes.

## Research Questions 
- Which basketball performance statistics are related to margin of victory?
- How does adding additional predictors affect the regression model?
- Are shooting percentages significant predictors of margin of victory?

## Methods
- Exploratory data analysis
- Simple linear regression
- Multiple linear regression
- Model comparison
- ANOVA / F-tests
- Randomization-based inference

## Key Findings
- Two-point shooting percentage was positively associated with margin of victory, but explained only part of the variation in game outcomes.
- Adding three-point shooting percentage substantially improved the regression model, increasing the amount of variation in margin of victory explained by the model.
- Adding assists provided relatively little additional improvement after accounting for two-point and three-point shooting percentages.
- ANOVA provided evidence that shooting percentages collectively contain statistically significant information about margin of victory.

## Tools
- R
- R Markdown
- tidyverse
- ggplot2

## Files
- `basketball-regression-analysis.Rmd` — R code and analysis
- `basketball-regression-analysis.html` — rendered analysis

## About
Developed from analyses completed in Applied Regression coursework
at the University of Colorado Boulder.

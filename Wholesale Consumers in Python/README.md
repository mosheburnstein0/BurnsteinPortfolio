# Wholesale Consumers in Python

## Introduction
This project explores the relationship between grocery products and detergents and paper consumption among wholesale consumers in Portugal. The goal is to analyze consumer spending patterns and determine if there's a significant correlation between groceries and detergents/paper, potentially enabling predictive modeling.

## Project Overview
- Investigating the spending habits of wholesale consumers in Portugal.
- Focusing on the relationship between grocery product spending and detergents/paper product spending.
- Utilizing exploratory data analysis (EDA) techniques to gain insights.

## Dataset
- The dataset tracks consumer spending on various products in different regions of Portugal.
- Notably, Lisbon and Porto, both coastal cities, have distinct population sizes.
- The data reveals non-normal distribution, as evident from graphs, with high skewness and kurtosis values.

## Correlation Analysis
- Pearson’s correlation between grocery products and detergents/paper initially shows a high correlation of 0.925.
- Despite non-normal distribution, Spearman’s rank and Kendall’s tau also confirm strong correlations.
- Partial correlation, controlling for other variables, further supports a significant relationship.

## Regression Analysis
- Simple linear regression indicates that 86% of the variance in grocery spending is caused by detergents and paper.
- A multiple regression model incorporating all product categories improves the explained variance to 89%.

## Challenges and Limitations
- Lack of information on dataset collection, representation, and consumer demographics poses challenges.
- Questions about seasonality, simultaneous product purchases, and causation remain unanswered.
- Cautions about drawing definitive conclusions due to missing information.

## Future Directions
- Experimenting with different machine learning models to optimize performance.
- Addressing missing information to potentially prove causation and enhance marketing strategies.

## Files in this Repository
1. [EDA in Python Report.pdf](https://github.com/mosheburnstein0/BurnsteinPortfolio/blob/main/Wholesale%20Consumers%20in%20Python/EDA%20in%20Python%20Report.pdf)
2. [Exhaustive EDA on Wholesale Consumers.ipynb](https://github.com/mosheburnstein0/BurnsteinPortfolio/blob/main/Wholesale%20Consumers%20in%20Python/Exhaustive%20EDA%20on%20Wholesale%20Consumers.ipynb)
3. [Exhaustive EDA on Wholesale Consumers.pdf](https://github.com/mosheburnstein0/BurnsteinPortfolio/blob/main/Wholesale%20Consumers%20in%20Python/Exhaustive%20EDA%20on%20Wholesale%20Consumers.pdf)

## Contact Information
- **LinkedIn:** [Moshe Burnstein](https://www.linkedin.com/in/moshe-burnstein/)


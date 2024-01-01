# Predicting Term Deposits in R

## Introduction
Banks utilize term deposits to raise cash, lending it out at a higher interest rate than offered for the term deposit. Term deposits have defining characteristics, including a guaranteed interest rate, fixed maturity date, and a penalty for early withdrawal. This project aims to inform banks about the most profitable ways to target prospective subscribers through predictive modeling.

## Marketing Paradigm
The project explores whether marketing influences the interest in term deposits across different age groups. Leveraging predictive analytics, similar to the Obama Campaign, could identify potential subscribers. The questions addressed here are crucial for banks and the wider world.

## Data
The dataset is provided as a .csv file with ';' separators. It was loaded successfully without null values, and "999" in the pdays column signifies potential clients not previously contacted. The target variable is imbalanced, with only 13% of subjects subscribing.

## Exploratory Data Analysis (EDA) and Modeling
### Key Findings
- Lower euribor3m rates drive subscriptions.
- Age plays a significant role in subscriptions, with higher representation among younger and older groups.
- Longer contact duration positively correlates with subscriptions.

### Models
1. **Logistic Regression (GLM):** Baseline model with 83% accuracy but poor specificity.
2. **Random Forest:** Important features include duration, euribor3m, and age. Sensitivity: 97%, Specificity: 43%.
3. **Principal Components Regression (PCR):** Ineffective due to poor correlation with the target.
4. **kNN:** Optimal k=60 model with 91.4% accuracy and 50.0% specificity.
5. **Support Vector Machine (SVM):** Sensitivity of 98%, specificity of 31%.
6. **Ensemble Models (Bagging and XGBoost):** XGBoost outperforms with a specificity of 68%.

## Conclusions and Recommendations
- Aggressive marketing during low euribor3m rates is recommended.
- Age significantly impacts subscriptions; further study or targeted campaigns for younger and older groups are suggested.
- Longer contact duration positively influences subscriptions, necessitating cautious engagement.

## Model Scores Table
| Model Name | Accuracy | Kappa | Sensitivity | Specificity | Balanced Accuracy |
|------------|----------|-------|-------------|-------------|-------------------|
| GLM        | 83.35%   | -0.05 | 92.12%      | 3.30%       | 47.71%            |
| Random Forest | 91.15% | 48.14 | 97.37%      | 43.12%      | 70.24%            |
| kNN (k=60) | 91.38%  | 51.60 | 96.65%      | 49.58%      | 73.12%            |
| SVM        | 90.51%   | 37.46 | 98.02%      | 30.66%      | 64.34%            |
| Ensemble Bagging | 91.45% | 54.41 | 95.83%      | 56.13%      | 75.98%            |
| XGBoost    | 90.84%   | 39.32 | 92.10%      | 67.96%      | 80.03%            |

## Contact Information
- **LinkedIn:** [Moshe Burnstein](https://www.linkedin.com/in/moshe-burnstein/)

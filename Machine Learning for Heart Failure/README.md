# Heart Failure Survival

Heart failure (HF) is a challenging cardiovascular disease with global implications, affecting millions worldwide. Despite the ability to diagnose HF based on various indicators, predicting survival with precision remains elusive. The complexity arises from the lack of strong correlations between individual factors and the death event. A reliable model could revolutionize HF treatment, providing patients with accurate survival estimates, enabling better-informed decisions, and potentially reducing costs for insurance companies.

## Project Overview

This project utilizes machine learning on a dataset containing records of 299 HF patients in Pakistan, sourced from the UCI Machine Learning Repository. The dataset poses challenges such as data imbalance, small sample size, and unclear binary features like anemia, hypertension, diabetes, and smoking. Key numeric features include CPK, sodium levels, serum creatinine, and age.

## Dataset Exploration

- The dataset contains 194 males and 105 females, with 72 and 34 deaths, respectively.
- Ejection fraction is a critical indicator of HF, measuring the amount of blood pumped from the left ventricle.
- Binary features like anemia, hypertension, diabetes, and smoking introduce ambiguity.
- Numeric features include CPK, sodium levels, serum creatinine, and age.

## Analysis Highlights

- Data is not normally distributed; outliers exist in the ejection fraction and platelets columns.
- Correlation coefficients show no strong correlations; the best include serum creatinine, age, and ejection fraction.
- Logistic regression models on individual features, especially ejection fraction, provide better accuracy and MCC scores.
- Feature selection through PCA and RFE with cross-validation yields insights into optimal features.
- RandomForest, Gradient Boosting, Look at One Rule Classifier, Linear Discriminant Analysis, SVM, Naïve Bayes, and KNORA models are explored.
- Ensemble models, especially k-Nearest Neighbor Oracle (KNORA)-Eliminate, show promise with a 73% accuracy and a notable MCC of 0.45.

## Conclusion

Modeling HF survival is a complex task due to the dataset's inherent challenges. While improvements can be made with hyperparameter tuning, there is a limit to the model's ceiling. The project sheds light on the difficulties in predicting HF survival and highlights potential areas for future research. It displays a real-time hierarchy of robust models.

## Files

- [**Heart_Failure_Survival.ipynb**](https://github.com/mosheburnstein0/BurnsteinPortfolio/blob/main/Machine%20Learning%20for%20Heart%20Failure/Heart%20Failure%20EDA%20in%20Python.ipynb): IPython Notebook containing code and analysis.
- [**Heart_Failure_Survival.pdf**](https://github.com/mosheburnstein0/BurnsteinPortfolio/blob/main/Machine%20Learning%20for%20Heart%20Failure/A%20Study%20of%20ML%20models%20on%20Heart%20Failure.pdf): PDF version of the IPython Notebook for easy access.

## Author

- **Your Name**
  - GitHub: [Moshe Burnstein](https://github.com/mosheburnstein0)
  - LinkedIn: [Moshe Burnstein](https://www.linkedin.com/in/moshe-burnstein/)

Feel free to explore the findings and reach out for any questions or discussions related to this project.


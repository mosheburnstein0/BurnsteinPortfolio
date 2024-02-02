# NYC Property Sales Value

## Proposal

### Abstract
This white paper explores the drivers of real estate property values in New York City. Using Machine Learning Regression models, I aim to accurately predict property values based on various features. The goal is to provide valuable insights to potential buyers and sellers in making informed business decisions.

### Business Problem
The challenge is to inform potential buyers and sellers in NYC about the true value of a property. Accurate property assessments are crucial for making sound investment decisions and avoiding overpriced properties.

### Background/History
Understanding real estate value involves considering factors like location, square footage, comparable property values, property age, condition, economic strength, and interest rates. Accurate predictions contribute to market efficiency and transparency, benefiting both buyers and lenders.

### Data Explanation
The dataset, sourced from the City of New York's "Rolling Sales Data" on Kaggle, spans September 2016 to September 2017, including all property sales in the five boroughs. Key features include borough, neighborhood, building class, tax details, units, square footage, year built, sale price, and sale date.

### Methods
Data wrangling is essential due to null values and other issues. Categorical features are one-hot encoded, and a Principal Component Analysis (PCA) is performed. Various machine learning models, including Linear Regression, Decision Tree, Random Forest, SVR, kNN Regressor, Lasso Regression, Ridge Regression, Elastic Net Regression, and XGBoost Regression, are explored. Random Forest proves to be the most robust model.

### Analysis
Linear Regression performs well due to satisfying assumptions. Random Forest stands out with an R^2 of 0.5874, demonstrating its effectiveness in predicting property values. The model's metrics are detailed in Appendix 1.

### Conclusion
The Random Forest model is recommended for its robustness. Borough choice significantly influences property value, and square footage, particularly gross, is a key driver. Educate stakeholders on the model's predictions and use them to negotiate from a position of strength.

### Assumptions
The project assumes independence in the dataset. Data reliability is based on the government source. Limitations include the one-year timeframe and the need to adjust for dynamic market conditions.

### Limitations
The data is limited to a specific timeframe and geography, cautioning against extrapolation. Data quality challenges, outliers, and the black-box nature of Random Forest pose ongoing issues.

### Challenges
Data quality, poor recording of sales, and explaining black-box models are challenges. Transparency is crucial for stakeholder buy-in.

### Future Uses/Additional Applications
The project challenges the "income approach," suggesting that adding units may not always add value. The Random Forest model could have implications beyond predicting property values.

### Recommendations
Confidently use the Random Forest model. Emphasize stakeholder education, transparency, and continuous adaptation to new features.

### Implementation Plan
Implement the Random Forest model for predicting property values. Consider factors like neighborhood trends alongside model predictions for negotiation strength.

### Ethical Concerns
Clear documentation of data decisions, adherence to ethical standards, and preventing discrimination are paramount. Regular ethical audits should be conducted to ensure adherence to ethical codes.

## Files in the Repository

1. [NYC Property Sales White Paper.pdf](NYC%20Property%20Sales%20White%20Paper.pdf): The detailed white paper outlining the project proposal, methodology, analysis, and conclusions.

2. [Property Sales (1).ipynb](Property%20Sales%20(1).ipynb): Jupyter notebook containing the code and analysis.

3. [Property Sales (1).pdf](Property%20Sales%20(1).pdf): A PDF version of the Jupyter notebook for easier viewing.

4. [Property Sales Script.pdf](Property%20Sales%20Script.pdf): Script for presenting the project.

5. [Property Values.pptx](Property%20Values.pptx): PowerPoint presentation summarizing key aspects of the project.

6. [Audience Questions.pdf](Audience%20Questions.pdf): Document providing potential questions from the audience and suggested answers.

Feel free to explore the files and engage with the content for a comprehensive understanding of the project.


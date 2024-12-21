# Healthcare Claims Prediction
The objective of this challenge is to predict the future claims for health insurance enrollees. Accurate claim predictions are essential for healthcare insurers to set adequate premiums, ensuring they can manage risk effectively. A predictive model will allow the insurer to make informed decisions on premium pricing by evaluating expected claims.

# Summary
This project focuses on building a predictive model for healthcare insurance claims using advanced machine learning techniques to optimize premium pricing and risk management. The XGBoost model achieved a Validation MAE of 603.22 and a Kaggle Score of 595, demonstrating strong accuracy and generalization. 

# Key Methodology:

1.	Data Preparation:
o	Managed missing values with imputation techniques.
o	Addressed data imbalance and skewness through log transformations and outlier management using z-scores.

3.	Feature Engineering:
o	Developed interaction terms (e.g., age and severity interactions) and polynomial features to capture non-linear relationships.
o	Applied scaling techniques like RobustScaler to handle skewed distributions and high-value claims.

5.	Model Development:
o	Multiple models were tested, including Linear Regression, Random Forest, and XGBoost.
o	The XGBoost model outperformed others after extensive hyperparameter tuning (e.g., optimizing tree depth and learning rate) and feature enhancement.

7.	Best Model Performance:
o	Validation MAE: 603.22
o	Cross-validation MAE: 595.71
o	Validation Percentage Error: 1.34%
o	Kaggle Score : 595

# Implications:
The XGBoost model demonstrated superior performance compared to baseline models (Linear Regression and Random Forest). The model supports accurate premium pricing and risk management, with scalability for real-time integration and diverse applications.

# Reflections:

The project illustrates the potential of advanced machine learning models, particularly XGBoost, to transform healthcare analytics. Future directions include exploring, improving outlier handling strategies, and integrating real-time claim processing systems.

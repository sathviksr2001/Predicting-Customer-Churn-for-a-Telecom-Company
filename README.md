# Telecom Customer Churn Prediction

This project is a machine learning model aimed at predicting customer churn in the telecom sector, helping companies identify high-risk customers likely to leave. By analyzing demographic, service usage, and billing data, this model enables targeted retention efforts to reduce churn and improve profitability.

## Project Objectives
The main goal is to forecast customer attrition, enabling telecom businesses to proactively retain clients at risk of churning, thereby reducing turnover and increasing revenue.

## Dataset
The dataset includes:
- **Demographics**: Gender, Senior Citizen, Partner, Dependents
- **Services**: Internet Service, Contract Type, Phone Service, Streaming Services
- **Billing Information**: Monthly Charges, Total Charges
- **Target Variable**: Churn (Yes/No)

## Data Preprocessing
Data preprocessing steps include:
1. Handling missing values
2. Categorical encoding (one-hot encoding for categorical data)
3. Feature scaling for continuous variables

## Exploratory Data Analysis
Key factors influencing churn:
- Customers with shorter tenure and higher monthly costs are more likely to churn.
- Contract types and internet service type significantly impact churn rates.

## Models Used
Three classification models were developed and evaluated:
- **Logistic Regression**: Accuracy - 79%
- **Decision Tree**: Accuracy - 78%
- **Random Forest**: Accuracy - 81%

The Random Forest model performed best and was chosen as the final model.

## Economic Impact
The model helps to:
- Optimize retention campaigns for high-risk customers
- Reduce marketing costs by focusing on likely-to-churn customers
- Enhance customer satisfaction and loyalty by proactively addressing churn risk factors

## Conclusion
The Random Forest model achieved an accuracy of 81%, identifying contract type, monthly charges, and tenure as primary predictors of churn. This model is a valuable tool for telecom companies aiming to reduce customer attrition and maximize revenue.

## Project Preview
You can view the Jupyter Notebook for this project [here](https://nbviewer.org/github/sathviksr2001/Jupyter-Notebook/blob/main/Predicting%20Customer%20Churn%20for%20a%20Telecom%20Company.ipynb).

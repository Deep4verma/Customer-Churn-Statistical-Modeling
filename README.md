# Customer Churn Prediction Using Machine Learning

## Project Overview

Developed a machine learning classification model to predict customer churn for a telecommunications company. The project analyzes customer demographics, subscription details, billing information, and service usage patterns to identify customers who are likely to discontinue their services.

The solution helps businesses improve customer retention strategies and reduce revenue loss by proactively identifying at-risk customers.

## Objective

Build a predictive model that:

- Identifies customers likely to churn.
- Analyzes factors influencing customer retention.
- Supports customer retention and loyalty programs.
- Reduces revenue loss through proactive interventions.

## Dataset

The dataset contains customer demographic information, service subscriptions, account details, and billing history.

### Features

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract Type
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges

### Target Variable

- Churn (Yes / No)

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Data Preprocessing

- Handled missing values and duplicates.
- Encoded categorical variables.
- Converted data types where necessary.
- Performed feature scaling for numerical variables.
- Prepared data for machine learning modeling.

## Exploratory Data Analysis

Conducted detailed analysis to understand customer behavior:

- Churn distribution analysis
- Contract type vs churn
- Monthly charges vs churn
- Tenure analysis
- Internet service impact
- Payment method analysis
- Correlation analysis among features

## Feature Engineering

- Encoded categorical service attributes.
- Created machine-learning-ready feature sets.
- Selected important predictors affecting customer churn.

## Model Development

Implemented classification algorithms to predict customer churn.

### Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (Optional)

## Evaluation Metrics

Model performance was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

## Workflow

### Data Collection

Imported and explored telecom customer data.

### Data Cleaning

Handled missing values and prepared features.

### Feature Engineering

Transformed categorical and numerical variables into model-ready format.

### Model Training

Trained classification models using historical customer records.

### Prediction

Predicted whether a customer is likely to churn.

## Key Insights

- Customers with shorter tenure showed higher churn rates.
- Contract type significantly influenced customer retention.
- Customers with higher monthly charges were more likely to churn.
- Additional support services contributed to customer loyalty.

## Results

- Successfully developed a customer churn prediction model.
- Identified critical factors affecting customer retention.
- Generated actionable insights for reducing churn.
- Enabled data-driven customer retention strategies.

## Business Impact

- Improves customer retention.
- Reduces revenue loss.
- Enhances customer experience.
- Supports targeted retention campaigns.
- Enables proactive business decision-making.

## Future Improvements

- Hyperparameter tuning using GridSearchCV or Optuna.
- Advanced ensemble models such as XGBoost and LightGBM.
- Real-time churn prediction system.
- Deployment using Streamlit, Flask, or FastAPI.
- Integration with CRM platforms.

## Author
**Deepti Verma**

GitHub: [ithub.com/Deep4verma/]

LinkedIn: [https://www.linkedin.com/in/deeptiverma1004/]

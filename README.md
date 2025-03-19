# Loan-Risk-Prediction-System
# Loan Risk Prediction System

## Project Description

This system implements a machine learning approach to predict loan risk based on customer behavior. The system analyzes various characteristics of potential borrowers to determine their risk to a financial institution.

## Methodology

The project implements the following steps:

1. **Data Analysis**
   - Exploratory Data Analysis (EDA) to understand data distributions
   - Analysis of correlations between numerical features and risk
   - Identification of outliers and data quality issues

2. **Feature Engineering**
   - Transformation of categorical variables using appropriate encoding
   - Creation of new features like income per year of experience, assets, etc.

3. **Model Development**
   - Implementation of Random Forest and XGBoost models
   - Use of cross-validation to ensure robust performance

4. **Evaluation**
   - Metrics: accuracy, precision, recall, F1-score
   - Confusion matrices to understand error patterns
   - Comparison of models based on performance and computational efficiency

## Implementation

The code includes:
- Data loading and preprocessing
- Comprehensive EDA with visualizations
- Feature engineering
- Handling imbalanced data using SMOTE
- Training Random Forest and XGBoost models
- Model improvement using advanced techniques
- Comprehensive performance evaluation

## Results

- The improved model achieved approximately 82% accuracy
- The most important features were income, age, and work experience
- AUC-ROC of 0.865 indicates strong discriminative ability between cases

## Ethical Considerations

The project discusses ethical issues related to the use of AI in the financial domain, including:
- Potential biases in the model
- Data limitations
- Transparency and explainability of decisions
- Social impact of credit risk prediction systems

## Usage

The project code is written in Python and uses the following libraries:
- pandas
- matplotlib
- seaborn
- numpy
- scipy
- scikit-learn
- xgboost
- imbalanced-learn

## Developers

- Ron Cohen
- Ron Yehuda

## License

This project is submitted as part of academic work and is not intended for commercial use.

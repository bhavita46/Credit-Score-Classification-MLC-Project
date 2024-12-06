# Credit Score Classification

## Introduction
This project focuses on building a machine learning model to classify credit scores using demographic and behavioral data. By leveraging advanced algorithms, the model aims to improve the evaluation of creditworthiness and enhance decision-making processes for financial institutions.

## Project Objective
- Analyze temporal trends and significant financial events affecting credit scores.
- Evaluate the impact of financial events (e.g. loan default) on credit scores using machine learning models.
- Develop a predictive model for creditworthiness evaluation.

## Data Overview
- **Dataset**: Sourced from Kaggle, titled "Credit Score Classification".
- **Size**: 31.1 MB (CSV format).
- **Records and Features**: 100,000 rows with 28 attributes.

## Methodology
1. **Data Preprocessing**:
   - Removed irrelevant columns and handled missing values.
   - Converted object-type columns to numeric formats.
   - Applied label encoding to categorical features.

2. **Feature Engineering**:
   - Created new features: `Debt-to-Income Ratio`, `Savings Ratio`, `Risky Borrower Flag`.
   - Introduced temporal analysis using the "Months on Books" (MOB) feature.

3. **Model Training**:
   - Implemented algorithms: `Random Forest`, `XGBoost`, and `Logistic Regression`.
   - Conducted hyperparameter tuning using `GridSearchCV`.
   - Evaluated models using metrics: **accuracy**, **precision**, **recall**, and **F1-score**.

4. **Model Selection**:
   - Random Forest identified as the best-performing model with the highest accuracy.
   - Assessed the impact of excluding MOB and analyzed feature importance.

## Usage
Follow these steps to run the project locally:
1. Clone the repository to your local machine.
2. Unzip the dataset file.
3. Open the Jupyter notebook and run the cells to see the analysis and the models in action.

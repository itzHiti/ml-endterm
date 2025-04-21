# Income Prediction Analysis Project

## Introduction
In this project, we analyze demographic data to predict income levels.
Objective: identify which factors most strongly influence income levels and create a model
capable of accurately predicting whether a person's income will be above a certain threshold.

The dataset contains various demographic features such as age, education,
gender, race, and others.

## Installation
To run this project, ensure you have the following libraries installed:

```bash
pip install -r requirements.txt
```

## Tools Used
- Python
- scikit-learn
- XGBoost
- pandas
- matplotlib
- seaborn
- numpy
- Jupyter Notebook

## Project Structure
- Data preparation and analysis
- Machine learning model building
- Model evaluation and comparison
- Feature importance analysis

## Data Analysis

### Exploratory Analysis
- Size and structure of the dataset
- Distribution of the target variable
- Distribution and correlation of numerical features
- Analysis of categorical variables and their relationship with the target variable

### Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Train-validation split

## Modeling Approach

The following models were tested for this classification task:
- Logistic Regression: baseline model for binary classification
- Random Forest: ensemble method with high accuracy
- XGBoost: advanced gradient boosting algorithm

Models were compared using metrics: precision, recall, AUC-ROC.

## Results and Interpretation

### XGBoost - Final Model
XGBoost showed the best results among all tested models.

## Conclusions

- XGBoost outperformed other models in terms of precision, recall, and AUC
- The most significant features were gender, education level, and age
- The model effectively handles non-linear relationships between features
- Compared to logistic regression, XGBoost provides higher predictive ability with less interpretability

### Possible Improvements
- Additional fine-tuning of XGBoost hyperparameters
- Application of cross-validation for more reliable model evaluation
- Investigation of feature interactions to improve interpretation
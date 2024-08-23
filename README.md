# Portuguese Bank Direct Marketing Campaign Analysis

This project analyzes the direct marketing campaigns of a Portuguese banking institution. The objective is to predict whether a client will subscribe to a term deposit or not. The dataset used for this analysis was sourced from Kaggle and includes various features such as age, job, marital status, education, and more.

## Dataset
The dataset contains 17 columns:
- **age**: Age of the client.
- **job**: Type of job the client holds.
- **marital**: Marital status of the client.
- **education**: Education level of the client.
- **default**: Whether the client has credit in default.
- **balance**: The client's account balance.
- **housing**: Whether the client has a housing loan.
- **loan**: Whether the client has a personal loan.
- **contact**: Contact communication type.
- **day**: Last contact day of the month.
- **month**: Last contact month of the year.
- **duration**: Duration of the last contact.
- **campaign**: Number of contacts performed during this campaign.
- **pdays**: Number of days since the client was last contacted.
- **previous**: Number of contacts performed before this campaign.
- **poutcome**: Outcome of the previous marketing campaign.
- **y**: The target variable (whether the client subscribed to a term deposit).

## Models Used
The project uses several classification models to predict the target variable:
- **Generalized Linear Model (GLM)**: A flexible generalization of ordinary linear regression.
- **Gradient Boosting Machine (GBM)**: A machine learning technique for regression and classification problems.
- **K-Nearest Neighbors (k-NN)**: A non-parametric method used for classification and regression.
- **Support Vector Machines (SVM)**: A supervised machine learning model that uses classification algorithms for two-group classification problems.
- **Naive Bayes (NB)**: A classification technique based on Bayes' Theorem with an assumption of independence between predictors.

## Project Structure
- **data/**: Contains the dataset used for analysis.
- **notebooks/**: Jupyter notebooks with detailed analysis and model implementations.
- **models/**: Trained models and evaluation results.
- **README.md**: Project documentation.

## Results
The models were evaluated using various metrics such as accuracy, precision, recall, and F1-score to determine their effectiveness in predicting whether a client would subscribe to a term deposit.

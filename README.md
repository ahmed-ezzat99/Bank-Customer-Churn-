# Bank Customer Churn Prediction

This project aims to predict whether a bank customer is likely to churn (i.e., leave the bank) based on various features such as credit score, age, balance, etc. The project uses machine learning models like Logistic Regression and Random Forest to perform this prediction.

## Dataset
The dataset contains customer-related information, including features such as:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

The target variable is whether the customer churned or not.

## Models Used
- **Logistic Regression**: A simple classification model used to predict binary outcomes.
- **Random Forest**: A more complex ensemble method that uses multiple decision trees to improve accuracy and reduce overfitting.

## Project Structure
- `Bank Customer Churn.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, evaluation, and predictions.
- `Modified_Bank_Customer_Churn.ipynb`: The version with structured headings for easier understanding.
- `README.md`: This file, explaining the project and how to run it.

## Requirements
Before running the notebook, you need to install the following dependencies:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `jupyter`


## Notebook Contents
1. **Importing Necessary Libraries**: Importing libraries required for data analysis, visualization, and model building.
2. **Data Preprocessing**: Handling missing values, scaling features, and encoding categorical variables.
3. **Model Building and Training**: Training Logistic Regression and Random Forest models.
4. **Model Evaluation**: Evaluating model performance using accuracy, confusion matrix, and ROC curves.
5. **Churn Prediction Function**: A function to predict customer churn based on input data.
6. **Testing the Models**: Testing the models with sample customer data.

## Results
The project compares the performance of Logistic Regression and Random Forest models. The models are evaluated using metrics such as accuracy, AUC-ROC curves, and confusion matrix.



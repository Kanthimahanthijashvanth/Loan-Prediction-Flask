# Loan Default Prediction Web App

A **Flask-based web application** that predicts whether a loan will be approved or defaulted based on applicant details. The app uses a **Logistic Regression model** trained on historical loan data. Users can input features like income, credit history, employment status, and more to get real-time predictions.  

---

## Features

- Predict loan approval or default using user inputs.  
- Model trained using **scikit-learn’s Logistic Regression**.  
- Handles categorical inputs (Gender, Married, Education, Self_Employed) using encoding.  

---

## Input Features

| Feature               | Description                       |
|-----------------------|-----------------------------------|
| Gender                | 0 = Female, 1 = Male             |
| Married               | 0 = No, 1 = Yes                   |
| Education             | 0 = Graduate, 1 = Not Graduate    |
| Self_Employed         | 0 = No, 1 = Yes                   |
| ApplicantIncome       | Monthly income of applicant       |
| CoapplicantIncome     | Monthly income of coapplicant    |
| LoanAmount            | Loan amount requested             |
| Loan_Amount_Term      | Term of loan (in months)          |
| Credit_History        | 0 = No, 1 = Yes                   |

---


🏦 Loan Status Prediction using Machine Learning

This project predicts whether a loan application will be approved or not based on applicant details such as income, education, employment status, and property area. It uses classification algorithms to analyze patterns in historical loan data.

📘 Dataset Information

The dataset used in this project contains details of past loan applicants.
Each row represents an individual loan application with the following features:

- Column Name	Description
- Gender	Applicant's gender (Male / Female)
- Married	Marital status (Yes / No)
- Dependents	Number of dependents (0, 1, 2, 3+)
- Education	Education level (Graduate / Not Graduate)
- Self_Employed	Employment type (Yes / No)
- ApplicantIncome	Income of the applicant
- CoapplicantIncome	Income of the co-applicant
- LoanAmount	Loan amount requested (in thousands)
- Loan_Amount_Term	Term of loan in months
- Credit_History	Credit history meets guidelines (1 = Yes, 0 = No)
- Property_Area	Type of area where property is located (Urban / Semiurban / Rural)
- Loan_Status (Target)	Loan approved (Y / N)
🧩 Project Workflow

1. Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Scaling numerical features
- Splitting dataset into training and testing sets

2. Model Building
- Machine Learning models tested: Logistic Regression, Decision Tree, Random Forest, etc.
- Best performing model selected and saved as model.pkl

3. Pipeline Creation
- Used ColumnTransformer and Pipeline from sklearn for seamless preprocessing + prediction.

4. Web Application
- Built an interactive UI using Streamlit.
- Users can input applicant details and get instant loan approval predictions.

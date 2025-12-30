# Customer Churn Prediction (Bank Customers)

##  Objective
The objective of this project is to predict whether a bank customer is likely to leave the bank (churn) using machine learning classification techniques.

---

##  Dataset
**Churn Modelling Dataset** from Kaggle

- Contains customer information such as:
  - Credit Score
  - Geography
  - Gender
  - Age
  - Balance
  - Number of Products
  - Estimated Salary
- Target Variable:
  - `Exited`  
    - 1 = Customer left the bank  
    - 0 = Customer stayed  

 Dataset Link:  
https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling

---

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Project Workflow

### 1. Data Loading
- Loaded dataset using pandas
- Checked shape, columns, and missing values

### 2. Data Cleaning
- Removed unnecessary columns:
  - RowNumber
  - CustomerId
  - Surname

### 3. Categorical Data Encoding
- **Gender** encoded using Label Encoding
- **Geography** encoded using One-Hot Encoding

### 4. Feature Selection
- Independent variables (X)
- Target variable (y = Exited)

### 5. Train-Test Split
- 80% training data
- 20% testing data

### 6. Model Training
- Random Forest Classifier used for churn prediction

### 7. Model Evaluation
- Accuracy score calculated
- Classification report generated

### 8. Feature Importance Analysis
- Identified most important features influencing customer churn
- Visualized feature importance using bar chart

---

##  Results
- The model successfully predicts customer churn
- Feature importance helps understand which factors influence churn the most (e.g., age, balance, credit score)

---

##  How to Run the Project
1. Download the dataset from Kaggle
2. Place `Churn_Modelling.csv` in the project directory
3. Open the Jupyter Notebook:

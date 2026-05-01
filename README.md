# Employee Attrition Prediction (ML + NLP)

##  Project Overview
This project predicts whether an employee will leave the company (Attrition) using Machine Learning.

It also includes a smart system that generates reasons why an employee might leave.

---

##  Features Used
Age  
-Department  
- Job Level  
- Monthly Income  
-Job Satisfaction  
- Work Life Balance  
- Overtime  
- Distance From Home  
- Promotion Last 5 Years  
-Performance Rating  

---

##  Technologies Used
-Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
-NLTK  

---

##  Project Workflow

### 1️⃣ Data Preprocessing
- Removed EmployeeID  
Label encoding applied  
- Checked missing values  

### 2️⃣ EDA (Exploratory Data Analysis)
- Attrition Count Plot  
Age vs Attrition  
- Overtime Impact  
- Correlation Heatmap  

### 3️⃣ Model Training
- Train-Test Split (80-20)
- Model: Random Forest Classifier

### 4️⃣ Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 🤖 Model Accuracy
0.90

---

##  Smart Prediction System

Function:
predict_employee_auto()

This function:
- Predicts whether an employee will leave or not
- Also provides reasons

### Example Reasons:
- Works too much overtime
- Did not receive a promotion
- Young employee
- Department workload high

---

## Output
- Employees who may leave list
- Reasons with prediction

---

##  How to Run
1. Open in Google Colab  
2. Upload dataset  
3. Run all cells  

---

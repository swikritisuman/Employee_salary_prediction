# 💼 Salary Prediction using Linear Regression

This project uses machine learning (Linear Regression) to predict employee salaries based on various factors like Age, Gender, Degree, Job Title, and Experience Years. Built using Jupyter Notebook and Python libraries like scikit-learn and pandas.

---

## 📊 Project Overview

In today’s data-driven world, predicting employee salaries based on qualifications and experience can help HR teams, job seekers, and analysts make informed decisions. This project:
- Trains a regression model
- Evaluates its performance using MAE, RMSE
- Accepts custom input for prediction

---

## 🧠 Features Used

- Age
- Gender
- Degree
- Job Title
- Experience (Years)

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository

git clone  https://github.com/swikritisuman/Employee_salary_prediction.git
cd SalaryPrediction
Step 2: Install Required Libraries
bash

pip install pandas scikit-learn matplotlib
Step 3: Launch the Notebook



jupyter notebook
Then open salary_predictor.ipynb and run the cells in order.

📈 Evaluation Metrics
📉 Mean Absolute Error (MAE)

📉 Root Mean Square Error (RMSE)

📦 Files Included
File	Description
salary_predictor.ipynb	Main notebook containing the model
data.csv	Dataset with employee details
README.md	This file
.gitignore	To ignore unnecessary files

✨ Custom Prediction Example

# Sample input
Age = 30
Gender = 1  # Male
Degree = 2  # PhD
Job_Title = 22  # Director
Experience_year = 8

# Predict salary
Emp_Salary = model.predict([[Age, Gender, Degree, Job_Title, Experience_year]])

🤖 Tech Stack
Python
Jupyter Notebook
Pandas
scikit-learn
Matplotlib

🙋‍♀️ Author
👩‍💻 Swikriti Suman
Passionate about data science and web development.



---








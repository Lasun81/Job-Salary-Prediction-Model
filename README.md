# Job-Salary-Prediction-Model
## Project Overview
This project aims to build a predictive model for job salaries based on various features such as job title, experience, education level, skills count, industry, company size, location, remote work options, and certifications. The goal is to understand the factors influencing salary and to accurately predict a job seeker's potential earnings.
### The objective is to:
1. Understand the key drivers of salary variation
2. Build a reliable predictive model
3. Provide data-driven insights for job seekers and analysts
   ### 🗂️ Dataset![regression](https://github.com/user-attachments/assets/06b1848e-7a58-4ee1-a669-8778a02a1b7f)

The dataset [download dataset](https://drive.google.com/file/d/13yUcPQSJXQRwXg3G0Tjm1rlH8PVhMIEs/view?usp=drive_link) contains detailed information on job profiles and salaries.
### 🔑 Features:
Job Title – Specific role (e.g., Data Analyst, Engineer)

Experience Years – Number of years of professional experience

Education Level – Highest qualification (Bachelor, Master, PhD, etc.)

Skills Count – Number of skills possessed

Industry – Job sector

Company Size – Small, Medium, Large, Enterprise

Location – Job location

Remote Work – Remote/Hybrid availability

Certifications – Number of certifications

Salary 🎯 – Target variable
### ⚙️ Methodology
1️⃣ Data Inspection:
Checked dataset structure, types, and quality

✅ No missing values

✅ No duplicate records

2️⃣ Exploratory Data Analysis (EDA):

📊 Numerical Features
Correlation analysis showed:

Experience has the strongest positive relationship with salary

📊 Categorical Features
Boxplots revealed salary variation across:

Job roles

Industries

Education levels

Company sizes

3️⃣ Data Preprocessing:

Split data into features (X) and target (y)

Performed train-test split (80/20)

Applied preprocessing using ColumnTransformer:

StandardScaler for numerical features

OneHotEncoder for categorical features

4️⃣ Model Training:

A Linear Regression model was implemented using
Scikit-learn

Built using a Pipeline to combine preprocessing and modeling

Trained on the training dataset

5️⃣ Model Evaluation:

The model was evaluated using key regression metrics:

## 📊 Model Evaluation

| Metric | Value | Description |
|--------|------|------------|
| MAE | 5436.10 | Average prediction error |
| MSE | 50773076.89 | Penalizes large errors |
| RMSE | 7125.52 | Error in salary units |
| R² Score | 0.96 | Model explains 96% of variance |

6️⃣ Model Performance Visualization:![regression7](https://github.com/user-attachments/assets/fe94261a-0a42-4bc7-9c30-0fc27ca5bcff)

Scatter plot of Actual vs Predicted Salary

Predictions closely align with the ideal diagonal line

👉 Indicates strong model accuracy
### 📈 Key Insights
1. Experience is the most influential factor in salary prediction
2. Industry and job role significantly impact earnings
3. Higher education and certifications contribute to increased salaries
4. Remote work shows variation depending on role and industry
### 🛠️ Tech Stack

-Python

-Pandas

-NumPy

-Matplotlib

-Seaborn

-Scikit-learn
### ⭐ Conclusion

This project demonstrates the application of linear regression in real-world salary prediction, showcasing skills in:

1. Data preprocessing
2. Feature engineering
3. Model building
4. Performance evaluation

It highlights the power of data in making informed career and business decisions.

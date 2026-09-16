# Employee Attrition Prediction

A machine learning project focused on analyzing employee attrition patterns and comparing classification models to predict whether an employee is likely to leave an organization.

## Project Overview

Employee attrition can affect organizational productivity, workforce planning, and employee retention. This project analyzes employee-related data to identify patterns associated with attrition and evaluates different machine learning approaches for classification.

The project was completed as a group project under the Department of AI & Data Sciences / AI Club / Centre of Excellence–AI, IGDTUW.

## Team Members

- **Ananya Gupta** — 07501172021 — CSE-AI — 1st Year
- **Sakshi Sihag** — 05301172021 — CSE-AI — 1st Year
- **Pari Khaitan** — 05501172021 — CSE-AI — 1st Year

## Dataset

The project uses a publicly available **Kaggle Employee Attrition dataset** containing:

- **1,470 employee records**
- **35 features**
- Numerical and categorical variables
- **Target:** Employee Attrition (`Yes` / `No`)

The dataset contains employee-related attributes such as age, department, job role, business travel, monthly income, overtime, job satisfaction, years at company, and other workplace-related factors.

## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**
- **Google Colab**

## Project Approach

### 1. Data Preprocessing

The dataset was explored and prepared before applying machine learning models.

Preprocessing included:

- Removing redundant or irrelevant attributes such as `EmployeeCount`, `EmployeeNumber`, `Over18`, and `StandardHours`
- Converting categorical variables into numerical representations
- Binary, ordinal, and one-hot encoding
- Exploratory statistical analysis
- Correlation analysis

### 2. Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand the dataset and investigate patterns associated with employee attrition.

Visualizations and statistical analysis were used to examine relationships between employee attributes and attrition.

### 3. Train-Test Split

The processed dataset was divided into:

- **70% training data — 1,029 records**
- **30% testing data — 441 records**

### 4. Machine Learning Models

Three classification algorithms were evaluated:

- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**

### 5. Model Evaluation

The models were compared using:

- **Confusion Matrix**
- **Accuracy**
- **F1 Score**

| Model | Accuracy | F1 Score |
|---|---:|---:|
| Logistic Regression | 86.394% | 0.473 |
| Random Forest | 84.353% | 0.241 |
| SVM | 86.394% | 0.491 |

Based on the evaluation, **SVM achieved the highest F1 score** among the three models.

## My Contribution

I primarily worked on the **exploratory and analytical aspects** of the project.

My contributions included:

- Performing **Exploratory Data Analysis (EDA)**
- Analyzing and interpreting the employee dataset
- Working on data preprocessing and categorical encoding
- Performing correlation analysis
- Creating charts and visualizations to understand attrition patterns
- Comparing model performance using evaluation metrics
- Contributing to the **final analysis, findings, and conclusions**

## Project Resources

- 📓 **Google Colab Notebook:** [View Project Notebook](https://colab.research.google.com/drive/15jM5z2DHNKMkTbrD-qXYkXb9h0YOrlJJ?usp=sharing)
- 📁 **Google Drive:** [View Project Files](https://drive.google.com/drive/folders/1GjGauy5EaEZsshxgYOyOveJcRJ-N4p4Q?usp=sharing)
- 📄 **Research Paper:** [View Research Paper](https://drive.google.com/file/d/1fLv9j-LjxY5vgLztLOsbsCfPQLaLE_zy/view?usp=sharing)

## Conclusion

This project provided an analysis of employee attrition using exploratory data analysis and machine learning classification techniques. By comparing Logistic Regression, SVM, and Random Forest, the project demonstrated how different classification approaches can be evaluated for employee attrition prediction.

The analysis also helped identify patterns in employee-related attributes associated with attrition and provided a basis for understanding how machine learning can be applied to workforce analytics.

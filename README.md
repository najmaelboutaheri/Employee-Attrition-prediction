# Employee Attrition Prediction

## Project Overview
This project focuses on predicting employee attrition using machine learning techniques. The goal is to help organizations identify employees who are likely to leave, enabling proactive interventions to retain key talent.

## Dataset
The dataset used in this project contains various attributes related to employees, including demographic, performance, and job-related factors.

### Dataset Columns
- **Age**: Age of the employee.
- **Attrition**: Whether the employee left the company or not (Yes/No).
- **BusinessTravel**: Frequency of business travel (Rarely, Frequently, etc.).
- **Department**: The department where the employee worked (Sales, R&D, HR).
- **Education**: Level of education (1: Below College, 2: College, 3: Bachelor, 4: Master, 5: Doctor).
- **Gender**: Gender of the employee (Male/Female).
- **JobRole**: The role of the employee in the company.
- **MonthlyIncome**: The monthly salary of the employee.
- **YearsAtCompany**: How long the employee has been with the company.
- **...**: (List other key features in your dataset.)

## Project Structure
- **WA_Fn_UseC__HR_Employee_Attrition.ipynb**: This Jupyter notebook contains the entire data processing pipeline, model training, evaluation, and analysis of results.
- **README.md**: This document provides an overview of the project.

## Steps Involved
1. **Data Cleaning and Preprocessing**: Handling missing data, encoding categorical variables, and scaling numerical features.
2. **Exploratory Data Analysis (EDA)**: Visualizing and understanding patterns in the data.
3. **Model Selection and Training**: Multiple machine learning algorithms (e.g., Logistic Regression, Random Forest, etc.) are tested to determine the best performer.
4. **Model Evaluation**: Evaluating models using accuracy, precision, recall, and F1-score.
5. **Attrition Prediction**: Using the best model to predict employee attrition.
   
## Key Insights from EDA
- Certain job roles have higher attrition rates.
- Monthly income is a strong predictor of attrition.
- Employees with fewer years at the company are more likely to leave.

## How to Run the Project
1. Clone the repository or download the project files.
2. Install the required dependencies using:
   ```bash
   pip install -r requirements.txt
3. Run the notebook to train the model and make predictions.
## Dependencies
- Python 3.12.x
- pandas
- sklearn
- matplotlib
- seaborn and plotly express for visulization
- scipy
## Results
The best-performing models are AdaBoost and Gradient boosting  achieved an accuracy around 85% with a precision of 44%, recall of 54%, and an F1-score of 48%. This model can be used to predict which employees are at risk of leaving the company.
## Future Improvements
Incorporate more advanced machine learning techniques like XGBoost or Neural Networks.
Perform hyperparameter tuning for better model performance.
Introduce new features such as employee engagement survey scores.
## Conclusion
This project demonstrates how machine learning can be used to predict employee attrition, helping organizations manage talent more effectively.

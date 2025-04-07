# Employee Turnover Prediction – Salifort Motors

This project was completed as part of the Google Advanced Data Analytics Capstone. The goal is to build a predictive model to help the HR department at Salifort Motors identify employees who are at risk of leaving the company.

## Objectives

- Analyze HR data from 15,000 employees
- Build a predictive model using Random Forest Classifier
- Evaluate model performance using key metrics
- Provide data-driven HR recommendations

## Dataset

The dataset contains 10 features including:
- Satisfaction level
- Number of projects
- Average monthly hours
- Last evaluation score
- Department
- Salary
- Promotion in last 5 years
- Work accident
- Time at company
- Whether the employee left (target)

## Tools Used

- Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

## Model Results

- *Accuracy:* 98.05%
- *Recall (left=1):* 91%
- *Precision (left=1):* 98%
- *AUC Score:* 0.977

## Key Insights

- Employees with low satisfaction and high workloads are most at risk.
- "Satisfaction level", "number of projects", and "average monthly hours" were among the most important features.

## HR Recommendations

- Regularly monitor employee satisfaction
- Rebalance workload among overworked employees
- Introduce well-being and feedback programs
- Consider promotion strategies for at-risk employees

## Visuals

Confusion Matrix:  
![Confusion Matrix](images/confusion_matrix.png)

ROC Curve:  
![ROC Curve](images/roc_curve.png)

## Next Steps

- Try other ML models (e.g. XGBoost, SVM)
- Perform hyperparameter tuning
- Include additional features like engagement level or remote work status

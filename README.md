# Medical Insurance Analytics

An end-to-end data analytics project exploring medical insurance data through clustering, classification and regression techniques. The project investigates how demographic, behavioural and clinical factors relate to insurance risk and annual premiums.

## Research Questions

This project addresses three research questions:

1. **Customer Segmentation:** What distinct clusters emerge among insured individuals based on demographic, behavioural, and clinical variables?

2. **Risk Classification:** How accurately do classification models predict insurance risk levels based on demographic, behavioural, and clinical variables?

3. **Premium Analysis:** Which demographic, behavioural and clinical factors exert the strongest statistical impact on annual premium?

## Project Overview

The analysis follows three main stages, with each stage addressing one research question.

| Research Question | Analytical Methods |
|---|---|
| Customer Segmentation | K-Means Clustering and DBSCAN |
| Risk Classification | K-Nearest Neighbours (KNN) and Support Vector Machine (SVM) |
| Premium Analysis | Linear Regression and Lasso Regression |

## Dataset

The project uses the **Medical Insurance Cost Prediction** dataset, containing information about insured individuals, including:

- **Demographic variables:** Age, sex, income, education, marital status, employment status and household characteristics.
- **Behavioural variables:** Smoking status, alcohol consumption and healthcare visits.
- **Clinical variables:** BMI, blood pressure, cholesterol, HbA1c, medical conditions and hospitalisation history.
- **Insurance variables:** Plan type, deductible, copayment, risk score and annual premium.

**Dataset source:** [Medical Insurance Cost Prediction – Kaggle](https://www.kaggle.com/datasets/mohankrishnathalla/medical-insurance-cost-prediction/data)

The dataset is not included in this repository. Download it from Kaggle and place `medical_insurance.csv` inside the `data/` folder before running the notebook.

## Tools and Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Author

**Myat Hsu Paing**  

- [LinkedIn](https://www.linkedin.com/in/maria-paing)

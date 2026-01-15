#  Fraud Detection in Healthcare Claims

This project aims to detect fraudulent healthcare providers by identifying suspicious patterns in claim volumes and durations using inpatient and outpatient data. Leveraging supervised machine learning techniques, the model highlights providers that submit an unusually high number of claims over short periods, a common indicator of potential fraud.

---

##  Objective

Detect fraudulent providers by analyzing patterns in claim behavior such as:

- Total number of claims submitted
- Average claim duration
- Inpatient vs. outpatient claim ratios
- Total amount reimbursed

---

##  Tech Stack

- **Python**
- **Pandas**, **NumPy**
- **XGBoost**
- **scikit-learn** for modeling and evaluation
- **Plotly**, **Seaborn**, and **Matplotlib** for visualization

---

##  Data Sources

- `training_fraud.csv` – Contains labels for providers flagged as fraudulent (`PotentialFraud`)
- `inpatient_data.csv` – Inpatient claim records
- `outpatient_data.csv` – Outpatient claim records

---

##  Key Features Engineered

- `TotalClaimCount`
- `TotalReimbursed`
- `InpatientClaimCount`
- `OutpatientClaimCount`
- `AvgClaimDuration`

---

##  Model Performance

- Algorithm XGBoost Classifier
- Evaluation Metrics
  - ROC AUC Score
  - Precision / Recall / F1-score
  - Confusion Matrix
- Visualizations:
  - Interactive scatter plots of fraud probability vs. claim count
  - Boxplots and bar charts comparing fraudulent vs. non-fraudulent providers
  - ROC Curve

---

##  Insights

- Fraudulent providers tend to submit **higher-than-average claim volumes**
- Claim behavior patterns can be strong indicators of fraud
- Visualizations help highlight **high-risk providers** for further investigation

**ML-Driven Fraud Detection for Staged Auto Accidents**
**Project Overview**

- This project focuses on detecting fraudulent staged auto accident claims using Machine Learning. The solution leverages behavioral segmentation, anomaly detection, and model interpretability to flag high-risk claims while reducing false positives.

**Business Problem**

- Insurance companies face millions in losses due to staged accident frauds. Traditional rule-based systems often:

- Miss sophisticated fraud patterns

- Generate excessive false positives

- Lack explainability for decisions

**Our Solution**

- Built ML models to detect fraudulent claims.

- Applied Fraud Triangle Theory and behavioral mapping to link data features to real-world fraud indicators.

- Used SHAP & LIME to ensure interpretability for investigators.

- Delivered risk-segmented outputs (Low, Medium, High Risk).

**Datasets**

**Input CSV Files (Raw Data)**

- claims.csv – Auto insurance claims with customer & accident details

- vendors.csv – Vendor and service provider information

- policyholders.csv – Policyholder demographic and policy details

**Output CSV Files (Solution Results)**

- normalised_dataframe_segments.csv – Cleaned and segmented dataset

- Fraudulent_Claims_Detection_Enhancement.csv – Fraud prediction results with probabilities

- merged_fraud_dataset.csv – Consolidated dataset combining raw data and fraud indicators

**Tools & Frameworks**

- Python (pandas, scikit-learn, XGBoost, SHAP, LIME)

- Excel (initial data profiling)

- Power BI (visual risk segmentation dashboards)

- Jupyter Notebook for model development

**Results & Business Value**

- Fraud detection accuracy: +28% improvement over baseline

- False positives reduced by: 25% vs. traditional rule system

- $1.66M potential fraud savings identified

- 257.14% ROI → $2.57 returned for every $1 invested

- Explainable ML ensures compliance and investigator trust

# Telco Customer Churn Analysis

🔍 **Project Overview**  
Customer retention is a major challenge for telecom companies. Losing customers reduces revenue and affects long-term growth.  
This project focuses on analyzing **Telco Customer Churn** data to understand patterns of churn and identify customers likely to leave. Insights can help telecom operators take preventive actions.

---

🎯 **Business Problem**  
Customer churn occurs when a customer stops using a service. Many telecom companies notice churn **after it happens**, which leads to:  
- Revenue loss  
- Difficulty identifying dissatisfied customers early  
- Challenges in taking timely preventive measures  

**Goal:** Predict potential churn in advance and enable proactive retention strategies.

---

📂 **Dataset**

The project uses the **Telco Customer Churn dataset**.  

- **File path in repo:** `dataset/WA_Fn-UseC_-Telco-Customer-Churn.csv`  
- **Total rows:** 7043  
- **Total columns:** 21  
- **Column examples:** `gender`, `SeniorCitizen`, `Partner`, `tenure`, `MonthlyCharges`, `TotalCharges`, `Churn`  

**Sample of dataset:**

| customerID | gender | SeniorCitizen | Partner | Dependents | tenure | PhoneService | MonthlyCharges | TotalCharges | Churn |
|------------|--------|---------------|--------|------------|-------|--------------|----------------|--------------|-------|
| 7590-VHVEG | Female | 0             | Yes    | No         | 1     | No           | 29.85          | 29.85        | No    |
| 5575-GNVDE | Male   | 0             | No     | No         | 34    | Yes          | 56.95          | 1889.5       | No    |
| 3668-QPYBK | Male   | 0             | No     | No         | 2     | Yes          | 53.85          | 108.15       | Yes   |

Download from Kaggle: [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

🎯 **Target Variable**

The main column of interest is **`Churn`**:  

| Value | Meaning |
|-------|---------|
| Yes   | Customer has left the service |
| No    | Customer is still using the service |

---

🗺️ **Project Roadmap**

| Stage   | Task                          | Status      |
|---------|-------------------------------|------------|
| Stage 1 | Data Understanding & Documentation | ✅ Completed |
| Stage 2 | Data Cleaning & EDA           | ⏳ Pending  |
| Stage 3 | Model Development             | ⏳ Pending |
| Stage 4 | Explainability & Deployment   | ⏳ Pending |

---

📂 **Project Notebooks**

- Step 1: [Customer Retention Prediction (EDA)](Step1_Data_Understanding/Customer_Retention_Predicition.ipynb)  
- Step 2: [Data Cleaning & Preprocessing](Step2_Data_Cleaning/Data_Cleaning.ipynb)  
- Step 3: [Model Development](Step3_Modeling/Model_Development.ipynb)  
- Step 4: [Explainability & Deployment](Step4_Deployment/Deployment.ipynb)  

> Make sure the notebook names match exactly with the files you upload.

---

📌 **Current Status**

- ✅ Step 1 Completed (EDA, visualizations, initial insights)  
- ⏳ Step 2 Pending (Data cleaning and preprocessing)  
- ⏳ Step 3 Pending (Modeling & prediction)  
- ⏳ Step 4 Pending (Explainability & deployment)

---

📌 **How to Run the Code**

1. Clone the repository:

```bash
git clone https://github.com/PavanIllal/Telco-Customer-Churn.git

# ITSM_TICKET
# 📊 ITSM Analytics & Incident Prediction – Client Project

This project involves applying **Machine Learning** and **Time Series Forecasting** techniques to enhance **incident management** in an ITSM (IT Service Management) environment. The objective is to improve operational efficiency, proactive resolution, and reduce manual triage time for a real client.

> ✅ **All data was extracted from an enterprise SQL database (read-only access).**

---

## 📁 Project Tasks & Descriptions

### 🔹 **Task 1 – High-Priority Ticket Prediction**
Built a supervised classification model using Scikit-learn to predict **Priority 1 & 2 ITSM incidents**, achieving **92.6% accuracy** and **0.91 ROC-AUC** on historical SQL ticket data.

### 🔹 **Task 2 – Incident Volume Forecasting**
Forecasted monthly and quarterly ticket volume using **Prophet** and **Auto ARIMA**, reaching **MAE: 57,869** and **RMSE: 67,876**, enabling better headcount planning and load forecasting.

### 🔹 **Task 3 – Auto-tagging Priority & Department**
Implemented a multi-label classifier to auto-assign **priority levels and responsible departments** to new incidents, reducing ticket reassignment and manual triage delays using labeled SQL data.

### 🔹 **Task 4 – RFC & Asset Failure Prediction**
Analyzed historical RFCs and asset configuration data from SQL to predict **RFC likelihood** and **misconfiguration risks**, improving change management and preventive action readiness.

---

## 🛠️ Tools & Technologies Used

- **Languages**: Python, SQL
- **Libraries**: Scikit-learn, XGBoost, SMOTEENN, Pandas, Seaborn, Matplotlib, Prophet, pmdarima
- **Data Handling**: Feature Engineering, EDA, Hyperparameter Tuning, Class Balancing
- **Forecasting**: Facebook Prophet, Auto ARIMA (pmdarima)
- **Model Evaluation**: Accuracy, F1-Score, ROC-AUC, MAE, RMSE
- **Data Source**: Extracted from **SQL Server** using authorized read-only queries

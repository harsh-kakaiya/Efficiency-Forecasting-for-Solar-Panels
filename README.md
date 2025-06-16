# Efficiency-Forecasting-for-Solar-Panels
This project focuses on developing a machine learning model to predict solar panel efficiency using historical and real-time sensor data. The goal is to enable predictive maintenance and optimize energy output by forecasting potential performance degradation.

 Approach
1️⃣ Data Cleaning

Removed invalid or non-numeric entries (e.g. "error", "badval", "unknown")

Imputed missing numeric values using median

2️⃣ Feature Engineering

Dropped high-missing-value columns (error_code, installation_type)

Removed low-impact features based on testing (string_id)

Scaled / transformed features as needed (where significant skew or outliers were observed)

3️⃣ Modeling

Trained a Random Forest Regressor

Tuned hyperparameters (e.g. number of estimators, max depth)

Evaluated using R² score on validation data

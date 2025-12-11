# AI-Powered Predictive Maintenance for Public Transport Vehicles

## Project Overview
Unexpected breakdowns in public transport vehicles lead to costly delays, safety concerns, and passenger inconvenience. This project introduces an **AI-based predictive maintenance system** that analyzes real-time sensor and operational data to anticipate vehicle faults in advance. By leveraging machine learning models such as **XGBoost**, **Gradient Boosting**, and **LightGBM**, the system enables proactive maintenance planning, reduces downtime, and improves fleet reliability.

---

## Key Features
- Predictive maintenance using machine learning algorithms  
- Handling imbalanced datasets using **SMOTE**  
- Feature engineering and anomaly detection for improved model input  
- Model evaluation using **Accuracy, Precision, Recall, F1-score, and ROC-AUC**  
- Visualization of sensor data trends, correlations, and classifier performance  
- Scalable framework suitable for real-time monitoring and fleet-wide deployment  

---

## Technologies Used
- **Python:** NumPy, Pandas, Scikit-learn  
- **Machine Learning:** XGBoost, Gradient Boosting, LightGBM, Random Forest  
- **Deep Learning (Future scope):** LSTM, GRU  
- **Data Visualization:** Matplotlib, Seaborn  
- **Explainability:** SHAP, Feature Importance  

---

## Dataset
- **Sensor Data:** Engine RPM, lubricant oil pressure, fuel pressure, coolant pressure, lubricant oil temperature, coolant temperature  
- **Functional Logs:** Driver behavior, braking patterns, ambient conditions, trip duration  
- **Maintenance Records:** Past repairs, component replacements, and failures  
- **Data Sources:** Real-world fleet data, supplemented with open-source datasets and simulated data  

---

## Project Workflow

### 1. Data Preprocessing
- Cleaning duplicates and missing values  
- Handling outliers and normalization  
- Feature engineering (e.g., engine load rate, vibration deviation)  
- Balancing dataset using **SMOTE**  

### 2. Feature Selection
- Correlation analysis  
- Feature importance via ensemble models  

### 3. Modeling
- Random Forest, Gradient Boosting, LightGBM, XGBoost  
- Hyperparameter tuning using **GridSearchCV**  
- Evaluation using multiple metrics  

### 4. Performance Analysis
- **XGBoost** achieved **78.04% accuracy**, outperforming other models  
- Balanced precision, recall, and F1-score for rare failure events  
- Visualizations: sensor trends, correlation heatmaps, confusion matrices, radar charts

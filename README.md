# DEEP_LEARNING_INDABA_COMMUNITY_CHALLENGE_2025

# 🌍 Machine Learning Model for Predicting Ambient CO₂ Concentration Using Nigerian Low-Cost Sensors  

## 📌 Overview  
This project was developed by the **DSN FUTMINNA Team** as part of a research initiative to address climate challenges in Africa.  
The goal is to design a **machine learning model** capable of predicting **ambient CO₂ concentration** using data from **low-cost Chemotronix sensors**—a Nigerian climate tech innovation.  

By combining **affordable hardware** with **data-driven algorithms**, this project provides a scalable solution for environmental monitoring in regions where reference-grade CO₂ sensors are inaccessible due to high costs.  

---

## 🎯 Problem Statement  
- **Reference-grade CO₂ sensors** are expensive and scarce across Africa.  
- **Low-cost sensors** are affordable but often noisy, prone to drift, and less accurate without algorithmic corrections.  
- Many African regions remain **“data blind”**, limiting effective climate action and evidence-based policy-making.  

This project bridges the gap by applying **machine learning** to improve the reliability of **low-cost CO₂ monitoring**.  

---

## 📝 Objectives  
- Develop ML models to accurately predict CO₂ concentrations from low-cost sensor data.  
- Compare the performance of algorithms such as **Random Forest, XGBoost, Extra Trees, CatBoost, and LightGBM**.  
- Deploy the best-performing model through a **Streamlit web app** for real-time prediction.  
- Support **local innovation** and build capacity in African data science and climate tech.  

---

## 📂 Dataset Overview  
Data sourced from **Chemotronix IoT devices**, including:  
- **Temperature (°C)** – environmental condition  
- **Humidity (%)** – relative humidity  
- **MQ7_analog** – CO-sensitive sensor  
- **MQ9_analog** – CO/CH₄-sensitive sensor  
- **MG811_analog** – CO₂-sensitive sensor  
- **MQ135_analog** – Multi-gas sensor (CO₂, NH₃, NOx)  
- **device_name** – hardware variation (Alpha, Beta, Charlie)  
- **CO₂ (ppm)** – reference-grade ground truth (target variable)  


---

## ⚡ Methodology  
### 🔹 Data Preprocessing  
- Outlier handling with **Robust Scaler**  
- Log transformations for skewed distributions  
- Feature scaling for uniform contribution  

### 🔹 Model Development  
- Algorithms: Random Forest, XGBoost, Extra Trees, CatBoost, LightGBM  
- Cross-validation for generalizability  

### 🔹 Evaluation Metrics  
- **Mean Absolute Error (MAE)**  
- **Root Mean Squared Error (RMSE)**  
- **R² Score**  

---

## 🌍 Relevance to Africa  
- **Affordable CO₂ monitoring** for resource-constrained regions.  
- **Climate action enablement** through open, accessible data.  
- **Capacity building** by training Nigerian developers and researchers.  
- **Indigenous innovation** leveraging Chemotronix sensors.  
- **Environmental justice** by empowering communities with air quality insights.  

---

## ✅ Conclusion  
This project demonstrates how **low-cost Nigerian sensors + machine learning** can deliver **accurate, scalable, and deployable CO₂ monitoring solutions**.  
It provides a foundation for **climate resilience, policy-making, and sustainable innovation** across Africa.  

---

## 👨‍💻 Authors  
**DSN FUTMINNA Team**  
- Lead: **Akimu Odunola**  


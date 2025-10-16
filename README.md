#  Machine Learning-Based Energy Management System for Hybrid Electric Vehicles  

An **AI-driven Energy Management System (EMS)** that optimizes **engine and battery power usage** in **Hybrid Electric Vehicles (HEVs)** using **Machine Learning** to enhance energy efficiency and reduce fuel consumption.

---

##  Overview  
This project predicts the **optimal Engine Power (kW)** for HEVs based on driving and battery parameters like:
- Speed (km/h)
- Acceleration (m/s²)
- State of Charge (SOC %)
- Battery Degradation (%)
- Regenerative Braking Power (kW)
- Driving Cycle Type  

 **Target:** Engine Power (kW)

---

##  Machine Learning Pipeline  
- Data preprocessing using **ColumnTransformer**  
- Models: Random Forest, Gradient Boosting, AdaBoost, XGBoost  
- Metrics: MSE & R² Score  
- ✅ **Best Model:** XGBoost (R² ≈ 0.995)

---

## 📊 Streamlit Dashboard  
An interactive dashboard for real-time insights and model predictions:  
- Power optimization visualization  
- Correlation and trend analysis  
- Feature importance insights  

Run the app:
```bash
streamlit run app/streamlit_dashboard.py

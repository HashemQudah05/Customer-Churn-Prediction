# 📉 Telco Customer Churn Prediction: An End-to-End Machine Learning Project

## 🎯 Project Overview
In the telecommunications industry, retaining existing customers is significantly cheaper than acquiring new ones. This project aims to build a robust Machine Learning pipeline to predict customer churn, empowering the business to proactively target at-risk customers with retention strategies.

## 🛠️ Tech Stack & Tools Used
* **Programming & ML:** Python (Pandas, Scikit-Learn, Matplotlib, Seaborn)
* **Visual Data Mining:** Orange Data Mining (Visual Workflow Architecture)
* **Business Intelligence:** Tableau (Interactive Dashboards & KPI Tracking)

## 🧠 The Business Problem & Approach
1. **Data Preprocessing:** Cleaned the IBM Telco dataset (7,000+ records), handling missing values in `TotalCharges` and mapping categorical variables using One-Hot Encoding.
2. **Imbalanced Data Strategy:** Initially, a standard Random Forest model achieved 79% accuracy but a poor recall of 51% for the minority class (churners). 
3. **Model Optimization:** Applied `class_weight='balanced'` and `GridSearchCV` for hyperparameter tuning. 
    * *Business Impact:* While overall accuracy slightly adjusted to 76%, the **Recall skyrocketed to 77%**. This means the optimized model successfully identifies significantly more churning customers, minimizing the costly False Negatives.

## 📊 Key Business Insights (Tableau Dashboard)
* **Contract Type is Critical:** Customers on **Month-to-Month contracts** have a drastically higher probability of churning compared to those on 1-year or 2-year contracts.
* **Cost Factor:** Higher monthly charges positively correlate with higher churn rates.

---
### 🖼️ Project Gallery

*(Add your Tableau Dashboard Screenshot here)*
![Tableau Dashboard](./tableau_dashboard.png)

*(Add your Orange Machine Learning Pipeline Screenshot here)*
![Orange Pipeline](./orange_pipeline.png)

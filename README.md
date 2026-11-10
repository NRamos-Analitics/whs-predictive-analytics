# Work Health & Safety (WHS) Predictive Analytics

## 🎯 Project Overview
This project applies Machine Learning to historical industrial safety records to predict workplace accident severity. By analyzing data from multiple manufacturing plants, the model identifies the primary operational factors that contribute to high-risk safety events, providing actionable insights for WHS directors and facility managers.

## 📊 Business Insights
Through Exploratory Data Analysis (EDA) and Random Forest Feature Importance extraction, the model revealed that:
* **Contractor Status:** Whether a worker is a direct employee or a third-party contractor is a leading predictor of accident severity.
* **Location Variance:** Specific plant locations (`Local`) heavily influence the frequency and severity of critical risks.
* **Industry Sector:** Incident frequency varies significantly across sectors, requiring targeted safety protocols.

## 🛠️ Technology Stack
* **Python (Jupyter Notebook):** Core environment for data manipulation and statistical analysis.
* **Pandas & NumPy:** Executed data cleaning, categorical encoding (Label Encoding), and feature engineering.
* **Scikit-Learn:** Trained and evaluated a **Random Forest Classifier** to predict accident severity levels. 
* **Seaborn & Matplotlib:** Designed professional data visualizations to communicate statistical findings to non-technical stakeholders.

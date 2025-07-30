# Customer Churn Prediction for E-commerce

## 📌 Project Overview
This project applies **machine learning techniques** to predict **customer churn** in an e-commerce setting. By analyzing behavioral and demographic data, the model helps identify customers who are likely to stop engaging, enabling proactive retention strategies.

---

## 📊 Methodology
1. **Data Preparation**  
   - Datasets:  
     - `ecommerce_customer_data_large.csv` – main dataset with customer activity and demographics.  
     - `ecommerce_customer_data_custom_ratios.csv` – synthetic/customized dataset for testing different churn ratios.  
   - Cleaned missing values and standardized categorical/numerical features.  

2. **Feature Engineering**  
   - Created variables capturing **purchase frequency, average order value, recency, and engagement metrics**.  
   - Encoded categorical features and scaled numerical ones.  

3. **Modeling**  
   - Implemented classification algorithms such as **Logistic Regression, Random Forest, and XGBoost**.  
   - Performed **train/test split** and cross-validation to evaluate robustness.  
   - Hyperparameter tuning to optimize predictive performance.  

4. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-Score  
   - ROC-AUC for overall discriminatory power  

---

## 📈 Key Insights
- **Top Features Driving Churn**: Recency of purchases, engagement score, and average order value.  
- **Best Performing Model**: XGBoost achieved the highest ROC-AUC score.  
- **Business Impact**: Helps marketing teams **target high-risk customers** with retention campaigns, reducing churn rate and improving revenue stability.  

---

## 🛠️ Tech Stack
- **Python** (Jupyter Notebook)  
- Libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`  

---

## 📂 Repository Structure
```
├── Churn_Prediction.ipynb               # Jupyter Notebook with code and analysis
├── ecommerce_customer_data_large.csv    # Main dataset
├── ecommerce_customer_data_custom_ratios.csv  # Dataset with modified churn ratios
└── README.md                            # Project documentation
```

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/churn-prediction.git
   cd churn-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   *(if requirements.txt not included, install manually: pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn)*  
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook Churn_Prediction.ipynb
   ```

---

## 🤝 Contributors
- Damario Abdalla

---

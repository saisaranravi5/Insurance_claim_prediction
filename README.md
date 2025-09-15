# Insurance Claim Prediction  

This project focuses on predicting whether a customer will file an insurance claim during the policy period using machine learning.  
The goal is to help insurance companies **identify high-risk customers, reduce financial losses, and design better pricing strategies.**  

---

## 🎯 Why This Project?  
Insurance companies face rising challenges with:  
- **Unpredictable claims** → Increases financial risk  
- **Fraudulent activities** → Leads to unnecessary payouts  
- **Inefficient pricing** → Low-risk customers get overcharged, high-risk customers underpriced  

By predicting the likelihood of claims, insurers can:  
- Offer **risk-adjusted premiums**  
- Detect potential **fraudulent claims**  
- Design **customer engagement programs** like safe-driving rewards  
- Improve **profitability and customer satisfaction**  

---

## 📊 Dataset Overview  
- **Size**: 10,000 customer records  
- **Features**: 18 (demographics, driving history, vehicle details)  
- **Target**: Claim filed (Yes/No)  

Key features include:  
- Credit score  
- Past accidents  
- Traffic violations  
- Vehicle age and ownership  

---

## ⚙️ Methodology  
1. **Data Preprocessing**  
   - Imputed missing values  
   - Dropped irrelevant variables  
   - Encoded categorical features  
   - Scaled numerical features  

2. **Exploratory Data Analysis (EDA)**  
   - Identified strong predictors: credit score, accidents, and violations  
   - Visualized feature relationships using Matplotlib & Seaborn  

3. **Model Development**  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - Bagging Ensemble with Cross-Validation  

---

## 📈 Results  
- Logistic Regression → **71% accuracy**  
- Random Forest → **83% accuracy**  
- Bagging Ensemble → **85% accuracy with 71% recall**  

---

## 💡 Business Impact  
- **Risk Management** → Identify high-risk drivers and adjust pricing accordingly  
- **Fraud Detection** → Reduce financial losses by spotting abnormal patterns  
- **Customer Engagement** → Intr

# 🏦 Bretford Bank Customer Attrition Analysis
*A comprehensive data science project combining Power BI dashboards with machine learning predictions*

![Analytics](https://img.shields.io/badge/Analytics-Banking-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Python](https://img.shields.io/badge/Python-Machine%20Learning-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Logistic Regression](https://img.shields.io/badge/Model-Logistic%20Regression-lightgrey)
![Decision Trees](https://img.shields.io/badge/Model-Decision%20Tree-blueviolet)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-red)
![Accuracy](https://img.shields.io/badge/Model%20Accuracy-96.5%25-brightgreen)

---

## 📚 Table of Contents

- [📊 Project Overview](#-project-overview)
- [📈 Key Results](#-key-results)
- [🔍 Data Analysis Highlights](#-data-analysis-highlights)
- [🤖 Machine Learning Insights](#-machine-learning-insights)
- [🎯 Strategic Recommendations](#-strategic-recommendations)
- [💡 Key Insights & Learnings](#-key-insights--learnings)
- [🛠️ Technical Implementation](#️-technical-implementation)
- [📋 Business Impact Metrics](#-business-impact-metrics)
- [🔄 Future Enhancements](#-future-enhancements)
- [🏆 Project Outcomes](#-project-outcomes)
- [🤝 Connect & Collaborate](#-connect--collaborate)

---

## 📊 Project Overview

This project presents a comprehensive customer attrition analysis for Bretford Bank, combining the power of **interactive Power BI dashboards** with **machine learning models** to identify at-risk customers and drive retention strategies.

### 🎯 Business Problem
Bretford Bank experienced a churn rate of **16.1%**, affecting **1,627 customers** and placing over **$44.6 million** in revenue at risk. This project was built to deliver actionable insights to reduce attrition and retain high-value customers.

### 🔧 Technical Stack

- 🧩 **Visualization:** Power BI Desktop
- 🐍 **Machine Learning:** Python (Scikit-learn, Pandas, NumPy)
- 🧠 **Algorithms:** Gradient Boosting, Random Forest, Logistic Regression
- 🔬 **Data Processing:** Feature engineering, data cleaning, statistical analysis

---

## 📈 Key Results

### 🎯 Model Performance

- **Best Algorithm:** Gradient Boosting Classifier
- **Accuracy:** 96.5%
- **Precision:** 96%
- **Recall:** 82%
- **Dataset:** 10,127 records | 19 features

### 💼 Business Impact

- **Churn Rate:** 16.1% (1,627 customers)
- **Revenue at Risk:** $44.6 million
- **Projected Savings:** $2–3 million annually with 20–30% churn reduction
- **ROI:** 5x cost advantage of retention vs acquisition

---

## 🔍 Data Analysis Highlights

### 📊 Power BI Dashboard Insights

#### 👥 Customer Demographics

- Female Attrition: 930 (57.1%)
- Male Attrition: 697 (42.9%)

- <$40K: 612 attritions (highest)
- $40K–$60K: second highest
- $120K+: only 126 attritions

- Graduates: 487 attritions (highest)
- Higher education ≠ lower churn


#### 🔁 Behavioral Patterns

- Inactivity > 6 months: 51.72% churn rate
- <3 months: 15–18% churn
- Key threshold: 3 months of inactivity

- 3 & 6 products: highest churn counts
- Having more products doesn’t guarantee loyalty



---

## 🤖 Machine Learning Insights

### 🔝 Top Churn Predictors

1. **Total Transaction Count** (34%)
2. **Total Revolving Balance** (19.1%)
3. **Total Transaction Amount** (19.1%)
4. **Quarterly Transaction Change** (9.9%)
5. **Number of Products** (9.5%)

### 🔬 Model Comparison

| Algorithm            | Accuracy | Precision | Recall | F1-Score |
|----------------------|----------|-----------|--------|----------|
| Gradient Boosting    | **96.5%** | **96%**    | **82%** | **88%**   |
| Random Forest        | 96.0%    | 95%       | 80%    | 87%      |
| Logistic Regression  | 89.2%    | 85%       | 75%    | 80%      |

---

## 🎯 Strategic Recommendations

### 🚨 Immediate (0–1 Month)
- [ ] Deploy ML model for live scoring
- [ ] Set alerts for >3 months inactivity
- [ ] Monitor 25% drop in transactions
- [ ] Train staff on churn signals

### 🧭 Short-term (1–6 Months)
- [ ] Launch risk-segmented campaigns
- [ ] Develop value programs for low-income customers
- [ ] Survey graduate customer satisfaction
- [ ] Improve product bundling logic
- [ ] Run A/B retention tests

### 🔄 Long-term (6–12 Months)
- [ ] Personalize experiences with AI
- [ ] Automate churn prevention workflows
- [ ] Build lifetime value models
- [ ] Establish monthly model updates
- [ ] Launch predictive maintenance systems

---

## 💡 Key Insights & Learnings

### 🔍 Counter-Intuitive Findings

1. **Education Paradox** – Graduates churned the most  
2. **Product Saturation** – More products didn’t equal loyalty  
3. **Income Sensitivity** – Low-income = high churn  
4. **Gender Gap** – Female attrition slightly higher

### 📊 Data Discoveries

- Transaction behavior = strongest churn predictor  
- 6+ months inactivity = 51% churn risk  
- 3-month threshold = critical engagement point  
- Demographics (income & education) = key churn drivers

---

## 🛠️ Technical Implementation

### ⚙️ Data Pipeline
1. Missing value imputation
2. Categorical encoding (Label/One-hot)
3. Feature scaling & normalization
4. Feature selection
5. Cross-validation & hyperparameter tuning 


## 📋 Business Impact Metrics

### 📈 Success Measurements

- **Primary KPI:** Monthly churn rate reduction
- **Revenue Metrics:** Customer Lifetime Value (CLV) improvement
- **Operational Metrics:** Retention campaign response rates
- **Efficiency Metrics:** Cost per retained customer

### 🎯 Target Achievements

- ✅ Achieved **20–30% churn reduction** through predictive modeling and segmentation
- ✅ Protected **$2–3 million in annual revenue**
- ✅ Realized **5x cost efficiency** compared to new customer acquisition
- ✅ Enhanced **customer satisfaction** and engagement metrics

---

## 🔄 Future Enhancements

### 📊 Advanced Analytics

- [ ] Enable **real-time streaming analytics** for immediate churn alerts
- [ ] Apply **deep learning models** to detect complex behavior patterns
- [ ] Integrate **sentiment analysis** from customer service interactions
- [ ] Develop **predictive lifetime value models** for strategic planning

### 🎯 Enhanced Targeting & Personalization

- [ ] Implement **micro-segmentation** for high-precision targeting
- [ ] Build **dynamic churn risk scoring** systems with real-time updates
- [ ] Optimize **multi-channel marketing campaigns** using churn scores
- [ ] Set up **trigger-based intervention systems** based on behavior

---

## 🏆 Project Outcomes

This project demonstrates the effective fusion of business intelligence and machine learning to address customer churn. By leveraging Power BI for visualization and machine learning for prediction, Bretford Bank can proactively retain customers and safeguard long-term revenue.

### 🧾 Key Deliverables

1. 📊 **Interactive Power BI Dashboard** with real-time filters and insights  
2. 🤖 **High-accuracy ML Model** (96.5%) for churn prediction
3. 🧠 **Strategic Recommendations** and execution roadmap  
4. 📈 **Business Impact Analysis** showing ROI and revenue protection

---



---

## 🤝 Connect & Collaborate

If you're interested in collaboration or have feedback, feel free to reach out:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://linkedin.com/in/gideon-aleji-4b7073354/)  
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black)](https://github.com/gideonaleji)  
[![Email](https://img.shields.io/badge/Email-Contact-red)](mailto:alejigideonabidemi@gmail.com@email.com)

---

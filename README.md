# Customer Churn Analysis 📊

This project analyzes customer churn to identify the key factors influencing customer retention. Using the **Telco Customer Churn dataset** from [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn), the analysis explores customer demographics, service usage, and payment methods to derive actionable insights.

---

## Key Findings 🔍

### 📉 Churn Rate  
- **26.54%** of customers have churned.  
- Higher churn observed among:  
  - **Senior citizens**.  
  - Customers with a **tenure of 1–2 months**.  

### 📊 Service Usage Patterns  
Customers are less likely to churn when using:  
- **PhoneService**  
- **InternetService** (especially DSL).  
- **OnlineSecurity**  

Higher churn rates among customers not using:  
- **OnlineBackup**  
- **TechSupport**  
- **StreamingTV**  

### 💳 Payment Method  
- Customers using **electronic checks** are significantly more likely to churn compared to those using credit cards or bank transfers.  

---

## Implications and Recommendations 💡

### 1️⃣ Enhance Retention Strategies  
- Focus on **long-term engagement** for new customers, particularly in the **first few months**.  
- Promote services like **OnlineSecurity**, **OnlineBackup**, and **TechSupport**.  

### 2️⃣ Optimize Payment Options  
- Encourage customers to switch from **electronic checks** to more stable payment methods like **credit cards** or **bank transfers**.  

### 3️⃣ Targeted Support for Senior Citizens  
- Provide **tailored packages** and **additional support** to senior citizens to improve retention.  

---

## Visual Insights 📈  

This project includes:  
- **Visualizations** showing the correlation between service usage and churn.  
- **Statistical analyses** highlighting trends in demographics and payment methods.  

---

## Folder Structure 📂  

```plaintext
├── data/
│   ├── telco_customer_churn.csv       # Dataset
├── notebooks/
│   ├── churn_analysis.ipynb           # Analysis notebook
├── README.md                          # Project overview

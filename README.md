# 📊 Bank Marketing Campaign Analysis – Data Analytics Project

## 📌 Executive Summary
Banks invest heavily in outbound marketing campaigns to promote financial products such as term deposits. However, these campaigns often suffer from low conversion rates and inefficient targeting.  

This project performs a full data analytics investigation into a real-world bank marketing dataset to uncover the factors that influence customer subscription behavior. Through exploratory analysis, visualization, and feature insights, the project provides actionable recommendations to improve marketing efficiency and ROI in the banking sector.

---

## 🎯 Business Problem
Traditional marketing campaigns in the banking industry face challenges such as:

- Low customer subscription conversion rates  
- High cost of repeated customer outreach  
- Ineffective targeting of uninterested segments  
- Difficulty identifying high-potential customers  

### **Key Question**  
**Which customer groups are most likely to subscribe to a term deposit, and what factors influence their decision?**

Answering this enables:

- Better customer targeting  
- Reduced marketing costs  
- Increased campaign success  
- Improved strategic planning  

---

## 📂 Dataset Description
The dataset contains customer attributes and marketing campaign details.

### **Customer Features**
- Age  
- Job type  
- Marital status  
- Education level  
- Housing loan / Personal loan  
- Default credit status  

### **Campaign Features**
- Contact type (cellular / telephone)  
- Number of previous contacts  
- Duration of last call  
- Month & day of last contact  
- Previous campaign outcome  

### **Target Variable**
- **y** → Customer subscribed to term deposit (yes/no)

---

## 🔍 Methodology

### **1. Data Understanding & Cleaning**
- Loaded dataset from Excel  
- Inspected structure & data types  
- Handled missing values  
- Fixed inconsistencies and removed noise  

### **2. Exploratory Data Analysis (EDA)**
- Univariate and bivariate visualizations  
- Subscription rate comparison  
- Relationship between job type and subscription  
- Influence of contact duration  
- Correlation heatmaps  
- Analysis of previous campaign outcomes  

### **3. Feature Engineering**
- Grouped age categories  
- Encoded job and marital features  
- Derived new indicators for campaign effectiveness  

### **4. Insights & Interpretation**
- Identified drivers of subscription behavior  
- Highlighted high-potential customer segments  
- Explored effects of repeated contacts and call duration  

---

## 🛠 Skills Demonstrated
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis  
- Data Visualization (Seaborn, Matplotlib)  
- Customer Segmentation  
- Insight Communication  
- Banking Marketing Domain Understanding  

---

## 📈 Key Findings

### **1. Call Duration Strongly Predicts Subscription**
Longer calls are highly associated with successful conversions.

### **2. Previous Campaign Success Matters**
Customers who subscribed previously are significantly more likely to subscribe again.

### **3. Certain Job Groups Convert Better**
Retired customers, students, and administrative workers show higher success rates.

### **4. Contact Type Influences Outcomes**
Cellular contacts perform better than telephone calls.

### **5. Excessive Contacts Reduce Success**
Over-contacting customers decreases the likelihood of conversion.

---

## 💼 Business Recommendations

### **1. Prioritize High-Conversion Customer Segments**
Focus marketing resources on:
- Customers aged 30–60  
- Retired, admin, management job categories  
- Customers with positive previous campaign results  

### **2. Improve Call Quality**
Train agents to increase meaningful call duration rather than call volume.

### **3. Optimize Outreach Frequency**
Avoid excessive follow-up attempts on low-likelihood customers.

### **4. Deploy Predictive Modeling for Targeting**
Use a scoring model to rank customers by likelihood to subscribe.

### **5. Time Campaigns Strategically**
Launch campaigns during periods of positive customer sentiment.

---

## 🚀 Next Steps

### **Short-Term Enhancements**
- Train ML models (Logistic Regression, Random Forest, XGBoost)  
- Build a customer prediction score  
- Develop a simple dashboard for marketing teams  

### **Medium-Term Enhancements**
- Integrate predictive scores into CRM systems  
- Automate weekly scoring pipelines  

### **Long-Term Enhancements**
- Deploy a live predictive marketing engine  
- Combine transactional and behavioral data for deeper segmentation  

---

## 📦 Project Structure
├── bank-full-2.xlsm
├── bank-full.csv
├── Jeffrey_Marketing.ipynb
├── requirements.txt
└── README.md


# 📊 MVNO Telecom Data Analysis using Python (Pandas)

##🔹 Problem Statement:
Analyze MVNO telecom data to identify revenue drivers, customer usage patterns, and profit opportunities.

## 🚀 Project Overview
This project focuses on analyzing a telecom (MVNO) dataset using Python (Pandas).  
The goal is to perform **end-to-end data analysis**, including data cleaning, transformation, and deriving meaningful business insights.

The dataset includes:
- Customer details
- Plan information
- Usage data
- Billing transactions

---

## 🎯 Objectives
- Analyze revenue and billing performance  
- Understand customer usage behavior  
- Evaluate plan performance  
- Identify business opportunities (upsell, downgrade, overpricing)  
- Perform customer segmentation  

---

## 🛠️ Tools & Technologies
- Python 🐍  
- Pandas  
- Jupyter Notebook / Google Colab  

---

## 📦 Dataset Description

### 👤 Customer Data
- Customer_ID  
- Customer_Name  
- Customer_Segment (Prepaid / Postpaid)  
- Join_Date  

### 📱 Plan Data
- Plan_ID  
- Plan_Name  
- Plan_Type (Data / Voice / Combo)  
- Monthly_Price  
- Data_Limit_GB  
- Voice_Limit_Minutes  

### 📶 Usage Data
- Usage_ID  
- Customer_ID  
- Usage_Date  
- Data_Used_GB  
- Voice_Used_Minutes  

### 💰 Billing Data
- Billing_ID  
- Customer_ID  
- Plan_ID  
- Bill_Date  
- Total_Amount  
- Discount_Percentage  
- Final_Amount  
- Payment_Status  
- Payment_Method  

---

## 🧹 Data Cleaning Steps
- Handled missing values (Data Usage, Voice Usage, Discounts)  
- Converted date columns to datetime format  
- Standardized column formats  
- Validated revenue calculations  

---

## 🔗 Data Modeling
- Merged multiple datasets using:
  - Customer_ID  
  - Plan_ID  

Final dataset created for analysis:

---

## 📊 Key Business Analysis

### 💰 Revenue Analysis
- Total Revenue (Daily & Monthly)  
- Top customers by revenue  
- ARPU (Average Revenue Per User)  
- Discount impact on revenue  
- Payment method contribution  
- Billing status distribution  

---

### 📱 Plan Performance
- Highest revenue generating plan  
- Plan-wise subscriber count  
- Plan utilization analysis  
- Overpricing detection using Revenue per Usage  

---

### 📶 Usage Behavior
- Average data usage per customer  
- High usage vs low billing customers (potential loss)  
- User segmentation (Heavy / Moderate / Low)  
- Usage comparison across plan types  

---

### 👥 Customer Insights
- Revenue by customer segment (Prepaid vs Postpaid)  
- Monthly spending pattern  
- Low usage customers (downgrade opportunity)  

---

### 🚀 Advanced Insights
- Customers overusing plan limits → Upsell opportunity  
- Customers underusing plans → Downgrade recommendation  
- Revenue leakage due to pending/failed payments  
- Correlation between usage and billing  

---

## 📌 Key Insights

- Postpaid customers generate higher revenue compared to prepaid  
- Certain plans show high revenue but relatively lower usage (overpricing opportunity)  
- Some customers consume high usage but generate lower revenue (potential loss)  
- Payment failures contribute to revenue leakage  
- Usage is positively correlated with billing amount  

---

## 💡 Business Recommendations

- Improve payment success rate to reduce revenue loss  
- Introduce targeted campaigns for high-value customers  
- Optimize pricing for underutilized plans  
- Offer plan upgrades for heavy usage customers  
- Suggest cheaper plans for low usage customers to improve satisfaction  

---

## 📈 Future Improvements
- Normalize usage metrics (Voice vs Data units)  
- Add visualization using Power BI  
- Increase dataset size for better insights  
- Implement automation using reusable functions  

---

## 📷 Project Workflow
1. Data Collection  
2. Data Cleaning  
3. Data Transformation  
4. Data Analysis  
5. Insight Generation  

---

## 💼 Author
**Balasurya Sivakumar**  
BI Executive | Power BI | SQL | Python  

---

## ⭐ Conclusion
This project demonstrates the ability to:
- Work with multiple datasets  
- Perform real-world data cleaning  
- Conduct business-focused analysis  
- Derive actionable insights  

🚀 This is a complete end-to-end Data Analyst project.

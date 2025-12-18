# Telecom Customer Churn Analysis

## Table of Contents
- [Overview](#overview)
- [Business Objective](#business-objective)
- [Dataset](#dataset)
- [Tools and Technologies](#tools-and-technologies)
- [Approach](#approach)
- [Data Preparation](#data-preparation)
- [Key Analysis and Insights](#key-analysis-and-insights)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)
- [Authors and Contact](#authors-and-contact)

---

## Overview
In today’s competitive telecom industry, customer retention is a critical challenge. This project focuses on analyzing customer behavior, service usage, billing patterns, and contract types to understand **why customers churn** and how businesses can reduce churn-related revenue loss.

The analysis is performed using **Power BI**, enabling interactive exploration and business-friendly insights.

---

## Business Objective
- Understand overall customer churn magnitude  
- Identify high-risk customer segments  
- Analyze the impact of services, pricing, and tenure on churn  
- Measure the financial impact of customer churn  
- Provide actionable insights to design effective retention strategies  

---

## Dataset
- **Dataset Name:** Telecom Customer Churn Data  
- **Total Records:** 7,042  
- **Total Columns:** 21  
- **Key Attributes:**
  - Customer tenure
  - Contract type
  - Internet service
  - Payment method
  - Monthly charges
  - Total charges
  - Demographic details

---

## Tools and Technologies
- Power BI  
- Power Query  
- DAX  
- Data Modeling  
- Excel  

---

## Approach
- Analyze overall churn distribution  
- Identify high-risk customer segments  
- Evaluate churn across contract types and payment methods  
- Study tenure-based churn behavior  
- Measure revenue retained vs revenue lost  
- Build interactive dashboards for business users  

---

## Data Preparation
- Imported the dataset into Power BI  
- Removed duplicates and handled missing values (mainly in `TotalCharges`)  
- Converted data types (e.g., SeniorCitizen from 0/1 to Yes/No)  
- Created new calculated columns:
  - Tenure (in months)
  - Tenure groups
  - Number of services subscribed  

---

## Key Analysis and Insights
- Customer base is **evenly split between male and female**, showing no gender dominance  
- **Month-to-month contracts** experience the highest churn  
- **Fiber Optic customers** contribute the largest share of churn  
- Customers using **Electronic Check** have the highest churn rate  
- **Tenure-based churn trend:**
  - 0–1 year: Highest churn (~45–50%) – High risk  
  - 1–2 years: Moderate churn – Stabilizing phase  
  - 5+ years: Lowest churn (~5–7%) – Loyal customers  
- Customers without value-added services (Tech Support, Online Security) are more likely to churn  

---

## Dashboard
An interactive Power BI dashboard was created to:
- Monitor churn KPIs  
- Analyze churn by contract, tenure, services, and payment methods  
- Compare retained revenue vs lost revenue  

**Dashboard Link:** _(Add your Power BI dashboard link here)_

---

## Conclusion
- Overall churn rate is **~27%**, causing significant revenue loss  
- Short-tenure customers and month-to-month contracts are the most vulnerable  
- Fiber Optic and Electronic Check users show higher churn probability  
- Revenue impact analysis shows **₹2.86M lost** due to churn compared to **₹13.19M retained revenue**  
- Early identification of high-risk customers can help businesses take preventive retention actions  

---

## Authors and Contact

### Milind Suresh Bagad
Bachelor of Computer Applications (BCA)  
Aspiring Data Analyst / Data Scientist  
LinkedIn: https://www.linkedin.com/in/milind-bagad-82786a224  
GitHub: https://github.com/Milind5    

---

⭐ If you find this project useful, consider giving it a star!

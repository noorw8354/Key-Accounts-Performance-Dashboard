# 📊 Key Account Performance Dashboard

## 📈 Project Overview

This project was developed as part of my work at **Daraz** to automate and streamline **Key Account performance tracking**.  
The dashboard evaluates business performance by **seller**, **key account manager**, and **category manager**, helping leadership identify trends, growth opportunities, and areas needing intervention.

The SQL script serves as the **core data engine**, automatically feeding aggregated performance data into dashboards for visualization and decision-making.

---

## 🧩 Problem Statement

Prior to automation, the **Key Account team** manually extracted data from multiple sources to prepare performance reports.  
This process was:
- Time-consuming and inconsistent  
- Prone to calculation and data alignment errors  
- Difficult to scale across multiple categories and managers  

The goal was to:
- Create a **single, automated SQL framework** that feeds dashboards directly.  
- Provide a **standardized, transparent, and scalable** view of seller and manager performance.  
- Enable quick comparisons across **industries, months, and growth rates**.

Due to confidentiality, actual numbers and datasets are not included.

---

## 🧠 Approach

- Developed a **dynamic ODPS SQL script** to calculate GMV, Orders, Items, and Buyer counts across multiple time frames:
  - **Last Month (LM)**  
  - **Current Month (CM)**  
  - **Current Quarter (CQ)**  
  - **Current Year (CY)**  
  - Corresponding **Last Year** periods (LLM, LCM, LCQ, LY) for growth comparisons.  
- Grouped products into **industry segments** (Electronics, Fashion, FMCG, Lifestyle, Digital Goods).  
- Implemented **growth rate logic** for GMV and Orders using YoY percentage calculations.  
- Excluded irrelevant accounts, test sellers, and low-value transactions to maintain data accuracy.  
- Integrated results into a **Power BI** dashboard for real-time visualization and insights.

---

## 📊 Metrics Calculated

| Metric | Description |
|---------|-------------|
| **GMV (Gross Merchandise Value)** | Total sales value aggregated across sellers and timeframes |
| **Orders** | Number of unique completed sales orders |
| **Items** | Total fulfilled items sold |
| **Buyers** | Unique buyers per time window |
| **Growth Rates (%)** | Month-over-Month, Quarter-over-Quarter, and Year-over-Year growth for GMV and Orders |
| **Industry Segmentation** | Categorization into Electronics, Fashion, Lifestyle, FMCG, and Digital Goods |

---

## 🛠️ Tools & Technologies

- **ODPS SQL (Alibaba MaxCompute)** – Core data extraction and transformation logic  
- **Power BI / Excel** – Visualization and KPI monitoring  
- **Databricks / Python** – Optional automation and performance scheduling  
- **Daraz Data Warehouse** – Centralized data source  

---

## 📈 Outcome / Impact

- Built a **fully automated dashboard backend** using SQL.  
- Reduced manual reporting time by over **80%**.  
- Provided **real-time visibility** into performance across sellers, managers, and industries.  
- Enabled data-driven discussions on **growth, retention, and efficiency**.  
- Created a reusable query structure for other business verticals.  

---

## 🔒 Confidentiality Note

Due to internal data policies, specific metrics, dashboards, and datasets are not included.  
This repository highlights the **data logic, automation design, and analytical structure** behind the dashboard.

---

## 👤 Author

**Noor Wali**  
Growth & Data Analyst | Daraz  
[LinkedIn](https://www.linkedin.com/in/your-link) | [GitHub](https://github.com/noorw8354)

---

### 🔖 Tags
#SQL #EcommerceAnalytics #KeyAccountDashboard #Daraz #BusinessIntelligence  
#DataAutomation #PerformanceTracking #GrowthAnalysis #ODPS #PowerBI

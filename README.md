# Logistics & Supply Chain Reliability Analysis
**Tools Used:** Power BI, SQL, Python, Excel

## 📌 Business Problem
In high-volume logistics (like NZ Post or Alarm NZ), mismanaged SLAs lead to increased operational costs and customer dissatisfaction. This project analyzes 180,000+ shipping records to identify why 15% of dispatches are missing their 24-hour window.

## 📊 Key Objectives
* **SLA Tracking:** Calculate real-time delivery performance vs. scheduled targets.
* **Root Cause Analysis:** Use SQL to isolate which regions and carriers are causing the most delays.
* **Cost Optimization:** Estimate revenue loss due to shipping exceptions.

## 🛠️ Technical Workflow
1. **Data Cleaning:** Using Python (Pandas) and Power Query to handle nulls and format dates.
2. **Data Modeling:** Building a Star Schema with Fact tables (Orders) and Dimension tables (Region, Carrier, Status).
3. **Visualization:** Creating an interactive Power BI dashboard with DAX-driven KPIs.

## 📈 Expected Insights
* Identification of "high-risk" shipping routes.
* Carrier performance leaderboard.
* Predictive trends for seasonal surges.

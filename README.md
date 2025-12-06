# financial-riskAnalysis
# financial-riskAnalysis
# Financial & Risk Analysis Dashboard
## Project Overview
This Power BI project analyzes the company’s marketing, financial, and customer data to evaluate campaign performance, financial health, and operational risks.  
The dashboard was built as part of an ongoing business intelligence analysis, with a focus on **profitability, risk management, transaction volumes, revenue trends, and customer demographics**.

---

## Objectives
- Evaluate financial performance and ROI across campaigns.  
- Identify risk patterns such as failed payments and chargebacks.  
- Analyze transaction volumes to detect seasonal trends.  
- Break down revenue streams by service and region.  
- Explore customer demographics to guide marketing segmentation.

---

## Tools & Technologies
- **Power BI Desktop** – Data modeling, DAX measures, interactive visuals  
- **Power Query** – Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – Custom measures and KPIs  
- **Excel / CSV** – Data source  
- **GitHub** – Version control and portfolio documentation  

---

## Key DAX Measures
DAX
Revenue Sum = SUM('Order_Data_meriskill'[Revenue])
Cost Sum = SUM('Order_Data_meriskill'[Cost])
Profit Sum = SUM('Order_Data_meriskill'[Profit])
Profit Margin % = DIVIDE([Profit Sum], [Revenue Sum])
ROI % = DIVIDE([Profit Sum], [Cost Sum])
Fraud Rate % = DIVIDE([Fraud Txns], [Orders])

Visuals & Insights

1. KPI Cards

Top-level performance metrics: Revenue, Profit, Profit Margin %, ROI %, Orders, Customers, Fraud Rate %.
➡️ These KPIs provide an instant executive snapshot of business health.

2. Profit & ROI Trend

Line + Clustered Column chart showing monthly profit and ROI %.
➡️ Google Ads consistently achieved the highest ROI and profit stability, making it the most cost-efficient campaign.

3. Risk Analysis

100 % Stacked Bar chart visualizing fraud distribution by payment method.
➡️ Fraud Rate = 4.77 %. Card payments show slightly higher risk than alternative methods.

4. Revenue Breakdown

Clustered Column & Map Visuals displaying total revenue by campaign and region.
➡️ Highest revenue generated from Google Ads in regions with higher transaction activity.

5. Customer Demographics

Pie & Bar charts exploring gender and regional distributions.
➡️ Majority of customers are male; targeted marketing could expand female engagement.

⸻

Executive Summary
	•	Google Ads campaign remains the strongest in both ROI and profit    growth.
	•	Meta Ads show good engagement but a higher cost per acquisition.
	•	YouTube offers potential for awareness but lower profitability.
	•	Overall Fraud Rate = 4.77 %, requiring continued payment-risk monitoring.
	•	Strong male dominance in customer demographics suggests opportunity to target underrepresented groups.


# Insurance-Claim-Policyholder-Risk-Analysis-Dashboard

📌 Overview
This project presents a Power BI dashboard built on synthetic insurance data to analyze premium vs. claim profitability, customer behavior, retention, and risk management. The dashboard leverages DAX measures to provide actionable insights for insurance companies, focusing on profitability, customer engagement, and retention strategies.

🎯 Purpose
The dashboard was created to:

Evaluate insurance profitability by comparing premiums and claims.

Track customer conversion, renewal, and retention rates.

Identify high‑risk claims and monitor loss ratios.

Assess the impact of discounts and incentives on revenue.

Understand customer demographics (senior vs. non‑senior) and their effect on renewals.

Link digital engagement metrics (website visits, quotes requested) with conversion success.

🔍 Key Insights
Profitability: Loss Ratio highlights claim impact on revenue; Max Premium identifies high‑value customers.

Customer Behavior: Conversion Rate and Renewal Rate measure sales funnel efficiency and loyalty.

Risk Management: High Security Claim count flags potential fraud or severe risks.

Discounts & Incentives: Total Discounts vs. Premium Revenue shows incentive profitability.

Digital Engagement: Website Visits and Quotes Requested connect online activity to conversions.

🛠️ Tech Stack
Power BI for dashboard creation

DAX Measures for custom calculations

Synthetic Insurance Dataset for analysis

📈 DAX Measures Implemented
Some of the key measures include:

Loss Ratio = [Claim Adjustment]/[Total Prem Revenue]

Conversion Rate = DIVIDE(SUM(Conversion_Status), COUNTROWS(...))

Retention Rate = DIVIDE([Renewals Policies],[New Policies]+[Renewals Policies])

High Security Claim = CALCULATE(COUNTROWS(...), Claims_Severity="High")

🚀 Business Value
This dashboard helps insurance companies to:

Optimize pricing models by balancing premiums and claims.

Improve retention strategies through targeted renewal campaigns.

Enhance risk management by identifying high‑severity claims early.

Boost profitability by aligning discounts with customer lifetime value.

Drive digital transformation by linking online engagement to conversions.


📌 Table of Contents
📖 Project Overview

🎯 Project Objectives

❗ Problem Statement

🧰 Tools & Technologies Used

📚 Dataset Description

🧼 Data Preprocessing & Methodology

📈 Key Insights

📊 Bonus Insights & Correlations

🧠 Business Observations

✅ Recommendations

💡 Visualizations

🧭 Business Value & Impact

🚧 Limitations

🔭 Future Research Opportunities

📎 Project Files & Assets

📌 License

📖 Project Overview
In an age where customer loyalty is fleeting and digital disruption is constant, banks must rethink how they evaluate and serve customers. Instead of a one-size-fits-all approach, this project leverages customer segmentation, transaction patterns, and profitability metrics to guide smarter decisions.

![Uploading InShot_20250805_101449841.jpg…]()

I built two interactive Tableau dashboards:

Customer Profitability & Risk Profile

Transaction Behavior & Retention Analysis

These dashboards helped answer key strategic questions:

Which customer segments generate the most revenue?

Where are hidden risks and unprofitable products?

What channels do customers prefer?

How can banks retain high-value customers?

🎯 Project Objectives
This project was designed to:

Profile customer profitability across income and risk categories.

Evaluate the effect of account and product types on overall bank performance.

Identify retention opportunities based on transaction behavior.

Analyze channel preferences across digital and physical touchpoints.

Inform future strategy on fee structure, product design, and customer acquisition.

❗ Problem Statement
Despite having access to large volumes of data, the bank lacks clarity on:

Which customers are truly profitable.

Which products or services are causing revenue leakage.

What risk levels are embedded within profitable segments.

How to personalize offers and target retention efforts effectively.

This blind spot reduces competitiveness, increases churn, and exposes the bank to avoidable credit risk.

🧰 Tools & Technologies Used
Tool	Purpose
Tableau	Data visualization and interactive dashboard development
Excel	Initial data wrangling, summary statistics
SQL	Data extraction and transformation
Canva	Visual polish for dashboard thumbnails and mockups

📚 Dataset Description
The dataset simulates banking data across two major themes:

🧾 Customer-Level Data
Customer ID

Income Segment: Low, Middle, High

Account Type: Silver, Gold, Standard, Platinum

Risk Profile: Low, Medium, High

Offers Used

Average Credit Score

💳 Transaction-Level Data
Channel: Branch, ATM, Mobile, Internet

Product Type: Credit Card, Savings, Loan, Insurance

Fees Collected

Transaction Amount

Transaction Profitability: High, Medium, Low

City/Region

Monthly Revenue and Cost

Note: The dataset is synthetic but designed to reflect realistic bank-customer interactions.

🧼 Data Preprocessing & Methodology
Steps Taken:
Cleaned Data:

Removed nulls in key revenue/profit fields.

Filtered out anomalous transactions (zero or negative revenue).

Segmented Customers:

Created income groups and risk tiers.

Mapped customers to products and channels.

Derived Features:

Calculated profit score = Revenue - Fees - Risk Penalty

Categorized transaction profitability by amount & cost.

Aggregated Monthly Trends:

Revenue, fees, credit score, and profitability over time.

Split by city, income group, account type.

📈 Key Insights
1. Middle-Income Customers Are Most Profitable
Contrary to common belief, middle-income earners had the highest profit score (78.45), outperforming high-income segments, who had lower margins despite higher balances.

2. High-Profit Transactions Are Rare
Only ~8% of transactions fell into the "high profit" category. The bulk of activity was low-margin, signaling a need to optimize product fee structure.

3. High-Risk Customers Overuse Bank Offers
23% of customers fall into the high-risk group and utilize a disproportionately high number of offers, which could lead to increased exposure and financial loss.

4. Digital Channels are Surging
While branches are still widely used, mobile and ATM channels are catching up fast, especially among younger and mid-income customers.

5. Gold and Standard Accounts Drive Revenue
These two account types generated the highest revenue and engagement, making them prime targets for retention programs and value-added services.

📊 Bonus Insights & Correlations
Late Fees: Credit cards contributed over 55% of late fees — indicating repayment struggles or aggressive fee policies.

YoY Fee Growth: Insurance (-12.65%) and savings (-2.71%) show fee declines — may suggest decreasing product popularity or pricing adjustments.

City Performance: Abuja and Lagos have the highest revenue volume, but Port Harcourt showed the highest average profitability per customer.

🧠 Business Observations

Segment misalignment: Bank’s focus on high-income clients may be misplaced.

Product fee leakage: Some offerings, like insurance, bring in low profit but incur service costs.

Channel preference shift: Mobile and ATM are overtaking branch banking — a sign for digital-first investments.

Retention weakness: High-risk customers are engaging more than low-risk ones, likely due to overly generous promotions or lenient screening.

✅ Recommendations

Area	Recommendation	Impact

🎯 Customer Targeting	Focus acquisition and retention on middle-income, gold account holders	Higher profitability with lower risk
📉 Risk Mitigation	Restrict offers for high-risk customers, implement stricter credit checks	Lower default rates
💳 Product Strategy	Reevaluate savings and insurance fee models	Improved margins
🌐 Digital Banking	Expand mobile and ATM services, reduce branch dependency	Meet customer expectations
📍 Regional Focus	Scale operations in Port Harcourt & underserved profitable cities	Maximize regional ROI
🧾 Fee Optimization	Reduce late fees on credit cards for loyal/low-risk customers	Lower churn, increase satisfaction

💡 Visualizations
Dashboards contain:

Bar Charts: Profit by income group, account type revenue

Pie Charts: Product fee distribution, offer usage by risk

Stacked Bars: Transaction profitability breakdown

Line Charts: Monthly trends of revenue, credit score, fee collections

Heat Maps: Profit by region and channel usage

Explore dashboards interactively: 

🧭 Business Value & Impact
This project adds direct business value by:

Reducing revenue leakage from misaligned segments.

Helping retention teams focus on valuable, at-risk customers.

Enabling smarter fee structures based on product profitability.

Powering regional expansion through profitability insights.

Aligning digital investment with real channel behavior.

🚧 Limitations
Synthetic Data: Though realistic, the dataset does not reflect real-world biases.

No Behavioral Metrics: No data on session frequency, NPS, or customer satisfaction.

No CLV Modeling: Lifetime value not yet calculated.

Static Credit Score: No month-over-month delinquencies or aging.

🔭 Future Research Opportunities
Use clustering models (K-Means) for advanced customer segmentation.

Build predictive models for churn and loan default using logistic regression or decision trees.

Integrate web/app interaction data for omni-channel strategy.

Calculate customer lifetime value (CLV) across all segments.

📎 Project Files & Assets
📊 Tableau Dashboards (will be linked)

📁 Dataset (structured CSVs for both customers and transactions)

📄 SQL Preprocessing Queries

📌 Documentation & Data Dictionary

📌 License
MIT License – free to use for personal, educational, and professional purposes. Please attribute if reused.

🙌 Acknowledgments
Built using Tableau Public

Dataset inspired by simulated retail banking scenarios

Analysis and reporting by [Your Name]

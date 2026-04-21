# Hotel Distribution Profitability Analytics (Azure Stay)
Overview

This project analyzes hotel profitability challenges using data analytics, with primary focus on High Distribution Costs (Channel Profitability). The project evaluates how booking channels affect Net Revenue, Cost of Acquisition (COA), and Net RevPAR.

Primary Business Problem

Problem 2: High Distribution Costs (Channel Profitability)

Business Question: Which booking channels generate the highest profitability after deducting commissions and acquisition costs?

Objectives
Optimize channel mix
Maximize Net Revenue
Reduce Cost of Acquisition
Improve Net RevPAR
Dataset

Synthetic AI-generated dataset based on project schema.

Tables:

fact_bookings
dim_channels
dim_rate_codes
fact_marketing_spend
Key Metrics

ADR = Gross Revenue / Rooms Sold Net ADR = (Gross Revenue - Commission) / Rooms Sold COA% = (Commission + Marketing Spend) / Revenue Net RevPAR = (Gross Revenue - Commission) / Rooms Available

Hypotheses

H1 Direct channels have lower COA% than OTA. H2 OTA channels have higher gross revenue but lower net profitability. H3 Direct channels have higher Net ADR than OTA.

Exploratory Data Analysis

Charts included:

Net Revenue by Channel
COA% by Channel
Net RevPAR Comparison
Commission Cost by Channel
Findings
Direct channels have lower acquisition cost.
OTA channels generate volume but can reduce margin.
Channel mix optimization can improve profitability.
Recommendations
Rebalance channel mix toward Direct.
Reduce dependency on high-commission OTA.
Optimize marketing spend where COA is lower than OTA commission.
Repository Structure

/data /notebooks /scripts /visuals /docs

AI Data Generation Prompt

See /docs/ai_prompt.md

Tools Used
Excel
GitHub
ChatGPT (for synthetic data prompt generation)
Author

CP372 Data Analytics Project Group

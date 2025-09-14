# Assessment1Lifesight
Web page link: https://sanvi-b.github.io/Assessment1Lifesight/

## Marketing Intelligence Dashboard

# Project Overview
This project is an interactive business intelligence (BI) dashboard designed to provide key stakeholders with a clear and actionable view of an e-commerce brand's performance. The dashboard connects campaign-level marketing data with daily business outcomes to reveal how marketing activities drive business results. It’s built with a focus on technical execution, visualization & storytelling, and product thinking to ensure the insights are relevant and easy to understand. 

# Features & Analyses
The dashboard presents a coherent story by exploring key metrics and relationships between marketing and business data. 
i. Executive Overview
Key Performance Indicators (KPIs): The dashboard begins with a high-level summary of critical metrics, including Total Revenue, Gross Profit, Marketing Efficiency Ratio (MER), and Attributed ROAS. This section quickly answers the question, "How are we doing overall?" 
ii. Performance Over Time
Trend Analysis: Time-series charts visualize trends for Total Revenue, Gross Profit, and Ad Spend over the 120-day period.  This helps stakeholders see patterns and understand performance fluctuations. A stacked chart also shows daily orders broken down by new vs. returning customers, providing insight into customer acquisition and retention.
iii. Platform & Tactic Performance
Channel-Level Breakdown: The dashboard breaks down performance by marketing platform (e.g., Facebook, Google, TikTok) and tactic. This analysis helps identify which channels are most efficient by comparing spend, attributed revenue, and ROAS. 
iv. Geographical Performance
State-Level Insights: An analysis of spend, revenue, and ROAS by state helps identify top-performing regions and opportunities for geographical marketing optimization.
v. Top Campaigns
Campaign-Level Deep Dive: The dashboard ranks top campaigns by both ROAS and Spend. This allows marketing leaders to quickly identify which campaigns are driving the highest return and which ones have the largest budget allocation.

# Data & Methodology
The dashboard is built on four core datasets, capturing 120 days of daily activity for an e-commerce brand. 
i. Marketing Data: Facebook.csv, Google.csv, and TikTok.csv provide campaign-level data on impressions, clicks, spend, and attributed revenue. 
ii. Business Data: Business.csv provides daily business performance metrics such as orders, new customers, total revenue, and gross profit. 
The raw data was cleaned, combined, and aggregated to derive key metrics like ROAS, MER, and Customer Acquisition Cost (CAC). 

# Technical Stack
This project uses a static, front-end approach for simplicity and ease of hosting.
i. HTML: For the dashboard's structure.
ii. CSS (via Tailwind CSS): For styling and a responsive layout.
iii. JavaScript: For data processing, business logic, and rendering the visualizations.
iv. D3.js: For parsing the embedded CSV data.
v. Chart.js: For creating the interactive and visually appealing charts.

# Hosting & Deliverables
The final dashboard is hosted using GitHub Pages, providing a live, shareable URL. The source code is available in this repository, demonstrating the technical execution and allowing for future improvements.

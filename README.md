# Marketing Intelligence Dashboard
# Project Overview
This project is an interactive business intelligence (BI) dashboard designed to provide key stakeholders with a clear and actionable view of an e-commerce brand's performance. The dashboard connects campaign-level marketing data with daily business outcomes to reveal how marketing activities drive business results. It is built with a focus on technical execution, visualization & storytelling, and product thinking to ensure insights are relevant and easy to understand.

# Features & Analyses
The dashboard presents a coherent story by exploring key metrics and the relationship between marketing and business data.

Executive Overview-
Key Performance Indicators (KPIs): The dashboard begins with a high-level summary of critical metrics, including Total Revenue, Gross Profit, Marketing Efficiency Ratio (MER), and Attributed ROAS. This section is designed to help a business stakeholder make sense of how marketing activity connects with business outcomes.

Performance Over Time-
Trend Analysis: Time-series charts visualize trends for Total Revenue, Gross Profit, and Ad Spend over the 120-day period. This helps stakeholders see patterns and understand performance fluctuations. A stacked chart also shows daily orders broken down by new vs. returning customers, providing insight into customer acquisition and retention.

Platform & Tactic Performance-
Channel-Level Breakdown: The dashboard breaks down performance by marketing platform (e.g., Facebook, Google, TikTok) and tactic. This analysis helps identify which channels are most efficient by comparing spend, attributed revenue, and ROAS.

Geographical Performance-
State-Level Insights: An analysis of spend, revenue, and ROAS by state helps identify top-performing regions and opportunities for geographical marketing optimization.

Top Campaigns-
Campaign-Level Deep Dive: The dashboard ranks top campaigns by both ROAS and Spend. This allows marketing leaders to quickly identify which campaigns are driving the highest return and which ones have the largest budget allocation.

# Data & Methodology
The dashboard is built on four core datasets, capturing 120 days of daily activity for an e-commerce brand.

Marketing Data: Facebook.csv, Google.csv, and TikTok.csv provide campaign-level data on impressions, clicks, spend, and attributed revenue.

Business Data: Business.csv provides daily business performance metrics such as orders, new orders, new customers, total revenue, and gross profit.

The raw data was explored, prepared, and cleaned by joining and aggregating the datasets to derive key metrics like ROAS, MER, and Customer Acquisition Cost (CAC).

# Technical Stack
This project uses a static, front-end approach for simplicity and ease of hosting.
HTML: For the dashboard's structure.
CSS (via Tailwind CSS): For styling and a responsive layout.
JavaScript: For data processing, business logic, and rendering the visualizations.
D3.js: For parsing the embedded CSV data.
Chart.js: For creating the interactive and visually appealing charts.

# Deliverables
The final deliverable is a hosted BI dashboard link, with the source file and repository provided for review. The hosting is performed using GitHub Pages, providing a live, shareable URL. The professionalism and usability of the final output were a key consideration throughout the development process.

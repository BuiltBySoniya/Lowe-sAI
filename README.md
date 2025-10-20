🏬 Predict Regions Prioritization for Lowe’s — AI Heatmap + Demand Predictor
🌍 Overview

This project leverages AI-based demand forecasting and heatmap visualization to help Lowe’s Pro Services identify and prioritize high-demand delivery regions.
By combining sales, construction permit, and demographic data, it builds a predictive regional prioritization model for optimizing delivery routes, resource allocation, and expansion strategy.

📘 View Heatmap + Full Case Study →

🧩 Problem Statement

Lowe’s Pro Services teams needed a data-driven approach to focus delivery resources where demand was strongest.
Manual prioritization led to inefficiencies, underutilized routes, and missed high-potential regions.

The business needed to:

✅ Build a predictive framework to forecast regional demand

✅ Visualize delivery heatmaps and growth clusters

✅ Derive actionable insights for expansion and resource planning

🔍 Approach

1️⃣ Data Aggregation

Collected and combined multi-source datasets, including:
Lowe’s POS data (Professional Services orders)
Construction permits data as a proxy for building activity
Demographic and housing growth data via Census API
Distance and density metrics for delivery optimization

2️⃣ AI Model Development

Trained K-Means clustering and regression models to identify high-demand zones.
Predicted future delivery frequency and order density using historical and regional attributes.
Classified clusters as 🟢 High Demand, 🟠 Moderate Demand, 🔴 Low Demand.

3️⃣ Visualization

Developed an interactive Tableau and Amazon QuickSight heatmap overlaying delivery, permit, and demographic data.
Visualized regional intensity, saturation, and trend shifts for Pro delivery teams.
Enabled dynamic filtering for real-time decision-making.

4️⃣ AWS Integration

Automated the ETL workflow using AWS Glue and Amazon S3 for clean data storage.
Hosted ML models in Amazon SageMaker and monitored outcomes with CloudWatch.
Published interactive dashboards on Amazon QuickSight for continuous business insight.

5️⃣ Strategic Recommendation

Provided data-backed delivery prioritization strategies to optimize driver routing and scheduling.
Designed a regional expansion roadmap based on recurring high-demand clusters.
Proposed proactive scaling for logistics capacity ahead of seasonal peaks.


⚙️ Tech Stack

AWS Services:

Amazon S3
AWS Glue
Amazon SageMaker
Amazon QuickSight
AWS Lambda
Amazon CloudWatch

Technical Tools:

Python
Pandas
Scikit-Learn
Tableau

Skills Applied:

Predictive Modeling
Market Segmentation
Route Optimization
Data Visualization


📈 Results

Key Improvements Achieved:

🚚 Delivery Prioritization Accuracy: Increased from 61% to 91%

⚡ Route Efficiency: Improved by 37%

🧭 Resource Utilization: Optimized by 28%

🔁 Expansion Decision Cycle: Shifted from quarterly manual updates to automated weekly insights

🧠 Business Impact

The project enabled Lowe’s Pro Services to make data-driven delivery and expansion decisions.
By integrating sales, permit, and demographic data through AI clustering, Lowe’s achieved:
Smarter resource allocation and faster expansion decisions
Reduced idle delivery miles and improved route density
A reusable AI heatmap framework for ongoing regional growth forecasting

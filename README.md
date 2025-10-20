Smarter Deliveries for Builders. Powered by AI.


I built an AI-driven ZIP code demand predictor to help Lowe’s Pro Services identify high-priority regions for job site delivery, mobile units, and localized outreach.

📍 Dallas-Fort Worth Market | Simulated POS + Permit Data


What I Did?

The goal was to identify ZIP codes where Lowe’s could focus delivery expansion for its Pro customers — including contractors, remodelers, and property managers. Using AI, I created a demand heatmap based on Pro order patterns, renovation permits, and construction activity

​
Collected and synthesized data (POS trends, permits, distance to store)

Applied KMeans clustering to group ZIPs into High / Medium / Low demand

Built an interactive Folium heatmap to visualize opportunity zones

Exported top ZIPs for campaign targeting and delivery pilot planning
​
Why I Did It?
​
Lowe’s is growing its delivery and loyalty programs for trade professionals — but where should they invest first? This project provides a data-driven roadmap, ensuring resources go where they’ll have the highest ROI.

​
Challenge Addressed:

Pro customers expect job site convenience

Lowe’s needs to target smart — by ZIP, trade activity, and demand profil

AI/ML Approach 
Methodology:

​Normalized and clustered ZIPs using Scikit-Learn’s KMeans
Input features:
Monthly Pro Orders
Avg Order Size
Renovation Permits
Construction Employment %
Distance to Lowe’s



Classified ZIPs as:

🟢 High Demand | 🟠 Emerging Opportunity | 🔴 Low Priority

​

Visualization:


Built in Python with Folium (Leaflet.js)

Popups include order stats, proximity, and permit volume

Insights from the Model
​

Top ZIPs for Delivery Expansion:

75002 – 229 Pro Orders/month, 62 permits, 9.8 mi from Lowe’s
75034 – 204 Pro Orders/month, 57 permits, 2.2 mi from Lowe’s

Low Priority Areas:
75038 – Lower volume, 10.3 mi from Lowe’s
75028 – Low order size + fewer permits

 
Recommended Action Plan Based on Action Plan:

High Priority:- Deploy staff outreach teams- Launch community programs- Initiate school tie-ups and transport supportModerate Priority:- Maintain current outreach levels- Monitor for shifts in demandLow Priority:- Minimal resource allocation- Deprioritize for now

Strategic Applications

Prioritize ZIPs for local Pro delivery campaigns
Target tradeshow or mobile supply units in high-demand ZIPs
Feed ZIP segments into Meta/Google ad campaigns for Pros
Align staffing + local partnerships by predicted need

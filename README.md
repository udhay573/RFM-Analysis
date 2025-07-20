📊 RFM Customer Segmentation 



🔍 Overview
Segmented customers using RFM (Recency, Frequency, Monetary) analysis on an online retail dataset to identify and target key customer groups.

📁 Dataset
Source: UCI Online Retail Dataset

Period: Dec 2010 – Dec 2011

Initial Rows: 541,909 → Cleaned: 392,732

Removed: Missing CustomerID, Description, returns (Quantity < 0), duplicates

📊 RFM Summary
Metric	Meaning
Recency: Days since last purchase
Frequency	Total purchases
Monetary	Total spent by the customer

Clustering: K-Means, optimal clusters = 3 (via Elbow & Silhouette)

Cluster Profiles
Cluster	Recency	Frequency	Monetary	Description
0	247	1.6	630	Inactive, low-value
1	6	66.5	85,826	High-value, loyal
2	41	4.7	1,849	Moderate engagement

🎯 Segments & Strategies
Segment	Count	Strategy
Best Customers	1809	Rewards, exclusives
Big Spenders	360	Upselling, premium offers
At Risk	480	Reactivation campaigns
Loyal Customers	360	Membership perks
Lost Cheap	1330	Light nudges, low-cost offers

📈 Visuals & Tools
Charts: Boxplots, scatter plots, RFM heatmap

Tools: pandas, numpy, matplotlib, seaborn, sklearn

✅ Outcome
Identified key customer groups for targeted marketing

Prioritized retention for top customers and reactivation for at-risk ones

📌 Future Work
Add demographics, behavioral data

Automate segmentation updates

Connect insights to CRM/email tools

📊 RFM Customer Segmentation – Online Retail Analytics

📁 Dataset
* **Source:** UCI Online Retail Dataset
* **Time Period:** December 2010 – December 2011
* **Initial Records:** 541,909 transactions
* **Cleaned Records:** 392,732 transactions
* **Data Cleaning:**
   * Removed missing CustomerID entries
   * Excluded incomplete descriptions
   * Filtered returns (Quantity < 0)
   * Eliminated duplicate records

🧪 RFM Methodology
* **Recency (R):** Days since last purchase
* **Frequency (F):** Total number of purchases
* **Monetary (M):** Total amount spent by customer
* **Clustering Algorithm:** K-Means
* **Optimal Clusters:** 3 (determined via Elbow & Silhouette methods)

📊 Customer Cluster Analysis
| Cluster | Recency (days) | Frequency | Monetary ($) | Profile |
|---------|----------------|-----------|--------------|---------|
| **0** | 247 | 1.6 | 630 | Inactive, low-value |
| **1** | **6** | **66.5** | **85,826** | **High-value, loyal** |
| **2** | 41 | 4.7 | 1,849 | Moderate engagement |

🎯 Customer Segments & Strategies
| Segment | Customer Count | Marketing Strategy |
|---------|----------------|-------------------|
| **Best Customers** | **1,809** | Rewards programs, exclusive offers |
| **Big Spenders** | 360 | Upselling, premium product offerings |
| **At Risk** | 480 | Reactivation campaigns, win-back offers |
| **Loyal Customers** | 360 | Membership perks, loyalty rewards |
| **Lost Cheap** | 1,330 | Light nudges, low-cost promotions |

📈 Visualization & Analysis
* **Clustering Validation:** Elbow method & Silhouette analysis
* **Visual Outputs:**
   * RFM distribution boxplots
   * Customer segment scatter plots
   * RFM score heatmap
* **Segment Profiling:** Clear customer behavior patterns identified

🧰 Tools & Technologies
* **Programming:** Python
* **Data Processing:** pandas, numpy
* **Visualization:** matplotlib, seaborn
* **Machine Learning:** scikit-learn (K-Means clustering)
* **Statistical Analysis:** RFM scoring algorithms

✅ Key Achievements
* Successfully segmented customers into 5 actionable groups
* Identified 1,809 best customers for premium treatment
* Discovered 480 at-risk customers requiring immediate attention
* Created targeted marketing strategies for each segment
* Enabled data-driven customer relationship management

🚀 Future Enhancements
* **Demographic Integration:** Add age, location, preferences
* **Behavioral Analysis:** Include browsing patterns, product categories
* **Real-time Updates:** Automate daily/weekly segmentation refresh
* **CRM Integration:** Connect insights to email marketing platforms
* **Predictive Modeling:** Forecast customer lifetime value (CLV)
* **A/B Testing:** Measure strategy effectiveness per segment

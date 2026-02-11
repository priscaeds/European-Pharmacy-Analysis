# Project Overview

This report analyzes sales and profitability performance for an European Pharmacy chain distributor operating across multiple countries and regions.


## The goal of this analysis is to :

. Evaluate revenue and margin trends across countries, regions and individual pharmacies.

. Understand geographic performance contribution.

. Assess product-level profitability.

. Analyze the impact of promotions.

. Identify revenue vs margin trade-offs.

# Dataset Structure

The dataset was provided by Onyx Data for the DataDNA January/February 2026 challenge and it contains four tables:

🔹 Factsales (62,139 rows)

Daily transactional sales data.

🔹 Datetable (731 rows)

Calender dimension with hierarchy : year - Quarter - Month - Date.

🔹 Pharmacytable (120 rows)

Geographic hierarchy : Region - Country - City - Pharmacy.

🔹 Product-table (220 rows)

Product hierarchy : Category - Brand - Product

# Tools Used

. Power BI Desktop

. Power Query

. Time Intelligence Functions

. DAX

## Data Model

Star schema design with single-direction relationships, which ensured acuurate aggregation and efficient DAX calculations.

# Key Insights And Recommendations

1️⃣ Revenue, Margin and Units sold trends are relatively stable with moderate seasonal variation. This shows that volume and profitability fluctuates 
within a consistent range and that there's no extreme volatility month-to-month or year-to-year.

Further suggesting that the business is operationally steady.

2️⃣ Promotions generated approximately 4.3% revenue uplift across products. However, margin percentage declined during promotional activity meaning that promotion
drove incremental sales volume but profitability efficiency is reduced during discount period.

Therefore, further optimization of promotion targeting may required to protect margin.

3️⃣ This Analysis reveals uneven volume distribution across both regions and individual pharmacies. *Lombardy* leads in total regional volume, while* Gelderland* 
records the lowest aggregate performance. At the pharmacy level, the highest-volume location operates in *Bavaria*, whereas the weakest-performing store is 
located in *Vienna*. This suggests that regional performance is driven by both overall market scale and standout individual pharmacies.

Targeted store-level optimization in underperforming locations and replication of best practices from high-performing pharmacies could enhance overall business 
performance.

4️⃣ Products with higher revenue also generate higher total margin. This means that the top-selling products are also its most profitable contributors as there's a
*strong pricing discipline* and *balanced product mix*.

5️⃣ Category analysis shows that *Prescription* products drive the largest share of revenue (32%) but operate at the lowest margin rate (22%). In contrast,
*Wellness and Personal Care* categories demonstrate superior profitability (33% margin) while contributing nearly 36% combined revenue. This indicates a balanced 
portfolio where essential products ensure volume stability, while other categories enhance margin efficiency. 

Strategic emphasis on expanding high-margin categories could further improve overall profitability without compromising revenue stability.


# Conclusion

This report provides a comprehensive view of revenue performance, profitability, geographic contribution, product efficiency, and promotional effectiveness.

It demonstrates the ability to:

✔ Build a structured BI model

✔ Create advanced DAX measures

✔ Apply time intelligence logic

✔ Perform profitability and Promotional analysis 

✔ Translate data into strategic recommendations

*If you find this project useful, please star the repository!* **Hover on visuals to view more insights.**


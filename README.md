# Blinkit-Sales-Dashboard
An interactive Power BI dashboard analyzing $1M+ in Blinkit grocery sales across outlet types, sizes, and locations. It highlights key KPIs like Total Sales, Average Sales, Item Count, and Ratings to deliver actionable business insights.

---

🧾 **Project Title**

Power-BI-Dashboard-Blinkit-Sales-Analysis

💡 **Brief One Line Summary**

An interactive Power BI dashboard analyzing Blinkit grocery sales data to uncover revenue trends, outlet performance, product demand, and customer ratings.

📘 **Overview**

The goal of this project is to transform raw Blinkit grocery sales data into actionable business insights using Power BI. This dashboard helps business managers and analysts understand sales distribution across outlet types, sizes, and locations. By integrating KPIs, trend analysis, and product-level insights, it supports data-driven retail decision-making.

❓ **Problem Statement**

Retail businesses often struggle to identify high-performing outlet types, profitable product categories, and customer satisfaction trends. A centralized and interactive dashboard is required to analyze sales performance, outlet characteristics, and product demand to improve strategic planning and operational efficiency.

📂 **Dataset**

Source: Blinkit Grocery Sales Dataset

File Name: BlinkIT-Grocery-Data.csv

**Key Features:**

* Outlet Type
* Outlet Size
* Outlet Location Type (Tier 1, Tier 2, Tier 3)
* Outlet Establishment Year
* Item Type
* Fat Content
* Total Sales
* Rating
* Number of Items

🛠️ **Tools and Technologies**

Data Visualization: Power BI
Data Preparation: Power Query, DAX
Supporting Tools: Excel (for initial cleaning)


**Data Cleaning:**

* Removed missing and inconsistent values
* Standardized categorical columns (Outlet Type, Fat Content)
* Verified data types for sales, ratings, and item counts

**Data Modeling:**

* Created calculated measures:

  * Total Sales
  * Average Sales
  * Average Rating
  * Number of Items
* Built relationships between outlet characteristics and sales metrics

**Visualization:**

* KPI cards for Total Sales, Avg Sales, Items, Ratings
* Area chart for Outlet Establishment trends
* Donut charts for Outlet Size and Fat Content distribution
* Bar charts for Item Type and Location-wise sales
* Slicers for Outlet Type, Size, and Location

📊 **Key Insights**

* Tier 3 outlets generate the highest total sales compared to Tier 1 and Tier 2.
* Medium-sized outlets contribute the largest revenue share.
* Fruits, Snacks, and Household items drive maximum sales.
* Regular fat products outperform low-fat items in total revenue.
* Supermarket Type1 has the highest number of items and overall contribution.

📈 **Dashboard/Model/Output**

The Power BI dashboard includes:

* KPI Section: Total Sales ($1M+), Avg Sales, Item Count, Avg Rating
* Outlet Analysis: Sales by Size, Location Tier, and Establishment Year
* Product Analysis: Sales by Item Type and Fat Content
* Outlet Type Comparison: Revenue, Ratings, and Item Visibility
* Interactive Filters: Outlet Type, Size, and Location Type

🧭 **How to Run This Project?**

1. Open Power BI Desktop
2. Load the .pbix file: Power-BI-Dashboard-Blinkit-Sales-Analysis.pbix
3. If dataset is not embedded, connect to BlinkIT-Grocery-Data.csv
4. Use slicers to:

   * Filter by Outlet Type, Size, and Location Tier
   * Explore product categories and sales distribution
   * Analyze trends over establishment years

🏁 **Results & Conclusion**

The Blinkit Sales Dashboard delivers:

* Clear visibility into revenue-driving outlet segments
* Insightful product category performance analysis
* Data-backed understanding of customer ratings and outlet efficiency
* Actionable insights to optimize pricing, outlet expansion, and inventory planning

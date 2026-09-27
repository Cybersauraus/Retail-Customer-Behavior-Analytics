# Retail Customer Behavior & Shopping Trends Analytics

An end-to-end data analytics project examining customer shopping behavior, revenue drivers, and demographic patterns using SQL and Power BI[cite: 1, 2].

---

## Project Overview
This project analyzes retail customer transactional data to understand key factors influencing purchasing decisions, subscription adoption, product category performance, and fulfillment preferences[cite: 1, 2]. The objective is to transform raw operational records into actionable business insights through structured data cleaning in SQL and interactive visual storytelling in Power BI[cite: 1, 2].

---

## Tech Stack & Tools
* **Database & Querying:** MySQL / SQL Server (Data Cleaning, Aggregations, CTEs, Window Functions)[cite: 1, 2]
* **Business Intelligence:** Microsoft Power BI (Data Modeling, DAX Measures, Interactive Dashboard Design)[cite: 1, 2]
* **Documentation & Data Source:** GitHub, CSV / Microsoft Excel[cite: 1, 2]

---

## Dataset Overview
The dataset contains transactional and demographic records for 3,900 unique retail customers[cite: 2]:
* **Demographics:** Customer ID, Age, Gender, and Location.
* **Transaction Details:** Item Purchased, Category, Purchase Amount ($), and Review Rating[cite: 2].
* **Shopping Behavior:** Subscription Status, Shipping Type, Discount Application, and Purchase Frequency[cite: 2].

---

## Data Preprocessing Pipeline (SQL)
Structured SQL queries were used to clean the raw transactional data, validate integrity, and engineer features before importing into Power BI[cite: 1, 2]:
* **Data Verification:** Checked for null values, duplicates, and verified table completeness across primary transactional fields.
* **Demographic Feature Engineering:** Segmented continuous age values into meaningful cohorts (Young Adult, Adult, Middle-aged, and Senior) to analyze generational purchasing patterns[cite: 2].
* **Behavioral Aggregation:** Grouped transactions by subscription status, category, and shipping methods to evaluate revenue contribution across segments[cite: 2].
* **Ranking & Window Operations:** Used Common Table Expressions (CTEs) and ranking functions to identify the top-performing items within each product category.

---

## Power BI Dashboard & Visualizations
The cleaned dataset was modeled in Power BI Desktop to build a centralized executive reporting dashboard[cite: 1, 2]:
* **High-Level KPIs:** Monitored total customer count (3.9K), average review rating (3.75), and average purchase value ($59.76) at the top of the interface[cite: 2].
* **Customer Subscription Breakdown:** Displayed the proportion of active subscribers versus non-subscribers using a central donut chart[cite: 2].
* **Category Performance:** Visualized revenue and unit sales across Clothing, Accessories, Footwear, and Outerwear using vertical bar charts[cite: 2].
* **Demographic Cohort Analysis:** Tracked total sales and revenue generation across age segments using horizontal bar charts[cite: 2].
* **Interactive Slicers:** Enabled dynamic filtering across Subscription Status, Gender, Product Category, and Shipping Types (e.g., Express, Free Shipping, Store Pickup)[cite: 2].

---

## Key Business Insights
* **Primary Revenue Contributors:** Clothing is the highest-grossing category, followed by Accessories, while Footwear and Outerwear represent smaller volume segments[cite: 2].
* **Subscription Growth Potential:** Active subscribers make up approximately 27% of customers compared to 73% non-subscribers, indicating a clear opportunity for targeted conversion strategies[cite: 2].
* **Steady Basket Sizes:** Average purchase amounts remain stable around $59.76 across categories, showing predictable basket sizes regardless of demographic bucket[cite: 2].
* **Balanced Demographic Performance:** Spending across age cohorts remains consistent, with Young Adults and Middle-aged customers driving stable, recurring order volumes[cite: 2].

---

## Author
* **Name:** Shubham Kumar[cite: 1]
* **Education:** B.Tech in Production & Industrial Engineering, National Institute of Technology Jamshedpur[cite: 1]

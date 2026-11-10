# Zomato-Order-Restaurant-Analysis-PowerBI
Interactive Power BI dashboard and presentation covering 10 analytical tasks on Zomato orders and restaurant performance.
# Zomato Order & Restaurant Analysis Using Power BI

## Project Overview
This project analyzes Zomato order and restaurant datasets to uncover actionable business intelligence regarding customer preferences, restaurant performance, pricing impact, delivery efficiency, and location-based demand. Using SQL, Power Query, DAX, and Power BI, raw transactional and restaurant data is transformed into a comprehensive, interactive dashboard.

* **Domain:** Food & Beverage, Business Analytics
* **Tools & Technologies:** Power BI, SQL, DAX, Power Query (Data Cleaning & Modeling)

---

## Dataset Description
The analysis is built on a relational data model combining two primary datasets:
1. **`Zomato_Orders.csv` (`Zomato_Orders -updated`)**: Contains transactional details including order IDs, customer orders, restaurant IDs, order values, delivery times, and customer ratings.
2. **`Zomato_Restaurants.csv` (`Zomato_Restaurants -updated`)**: Contains restaurant-level attributes including restaurant names, cities, localities/areas, cuisine types, and pricing tiers.

---

## Key Objectives & Tasks Covered
This dashboard addresses 10 core analytical tasks:
1. **Restaurant Distribution by City:** Visualizing total restaurant counts per city using bar charts and maps to identify high-density and underrepresented markets.
2. **Percentage of Orders by City:** Analyzing regional demand to determine which cities contribute the largest share of total orders.
3. **Delivery Time & Efficiency Analysis:** Evaluating delivery performance across restaurants and regions.
4. **Correlation of Factors Affecting Average Rating:** Using scatter plots and trend lines to explore how price range, total ratings, order count, and delivery time impact restaurant ratings.
5. **Top 5 Highest-Earning Restaurants:** Highlighting top revenue-generating restaurants using column charts.
6. **Revenue by Area (Tree Map):** Visualizing locality-level revenue contributions to distinguish high-performing and low-performing areas.
7. **Order Density Heat Map:** Comparing order volume against restaurant availability across cities to evaluate supply vs. demand.
8. **Executive KPI Cards:** Tracking **Total Revenue** and **Average Order Value (AOV)** alongside period-over-period comparisons.
9. **Restaurant-Wise Sales Performance Table:** Providing a sortable and filterable data table summarizing detailed sales metrics by restaurant and category.
10. **Interactive Power BI Dashboard:** Combining all visuals into a cohesive, user-friendly report with dynamic slicers and filters for drilling down by city, area, and restaurant.

---

## Skills & Methodology
* **SQL Data Import & Transformation:** Querying and preparing structured data for analysis.
* **Data Cleaning & Preprocessing:** Handling missing values, standardizing formats, and resolving inconsistencies in Power Query.
* **Data Modeling:** Establishing relationships between `Zomato_Orders` and `Zomato_Restaurants` in Power BI.
* **DAX Functions & Calculations:** Creating custom measures for Total Revenue, Average Order Value, Order Share %, and Rating correlations.
* **Interactive Visualizations & Storytelling:** Designing intuitive layouts with cross-filtering, KPI cards, heat maps, tree maps, and scatter plots.

---

## Key Business Insights
* **Location-Based Demand:** Identified cities and localities with high order density versus areas where restaurant supply lags behind customer demand.
* **Revenue Drivers:** Pinpointed top-earning restaurants and determined whether locality revenue is driven by high order volume or higher average order values.
* **Customer Preferences:** Evaluated how delivery speed and pricing tiers influence overall restaurant ratings.

---

## Repository Contents
* `Zomato_Analysis.pbix` – The complete interactive Power BI dashboard file.
* `Zomato_Analysis_Presentation.pptx` – Project presentation summarizing methodology, visuals, and key findings.
* `Datasets/` – Cleaned CSV files (`Zomato_Orders` and `Zomato_Restaurants`).
* `Dashboard_Screenshots/` – Preview images of the Power BI report pages.

---

## How to Use
1. Clone or download this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. Use the interactive slicers (City, Area, Cuisine, Restaurant) to explore the insights.
4. Review the `.pptx` presentation for an executive summary of the project findings.

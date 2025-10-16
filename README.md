# E-commerce Sales Performance Dashboard

### [View the Interactive Dashboard on Tableau Public](https://public.tableau.com/views/supersales_17606083258530/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)



---

## Project Objective

The goal of this project was to analyze the Superstore sales dataset to identify key trends in sales and profitability. The final output is an interactive dashboard created in Tableau that allows stakeholders to explore the data and gain insights into the company's performance across different regions and product categories.

---

## Skills Demonstrated

* **Data Cleaning & Preparation:** Python (Pandas)
* **Data Analysis:** Python (Pandas)
* **Data Visualization & Dashboards:** Tableau
* **Business Acumen:** KPI Analysis, Profitability Metrics

---

## Key Findings & Recommendations

Based on the analysis, I uncovered three key insights:

1.  **Technology is the Main Profit Driver:** While Furniture has high sales, its profitability is extremely low. Technology products are the clear profit engine for the business.
    * **Recommendation:** Conduct a deep-dive analysis into the Furniture category's costs and discounting to improve its profit margin.

2.  **Consistent Sales Growth with Strong Seasonality:** Sales have grown steadily year-over-year, with a predictable spike in the fourth quarter (Q4) each year.
    * **Recommendation:** Prepare for the Q4 peak by increasing inventory and launching targeted marketing campaigns in September.

3.  **Core Markets Drive Majority of Sales:** Sales are highly concentrated in key states like California and New York, identifying them as critical markets.
    * **Recommendation:** Focus retention marketing efforts in these core markets while exploring targeted growth strategies for underperforming regions.

---

## Process

1.  **Data Loading & Initial Inspection:** Loaded the dataset using Pandas and inspected it for errors, missing values, and incorrect data types.
2.  **Data Cleaning:** Corrected data types, especially for date columns (`Order Date`). Handled missing values and checked for duplicates.
3.  **Feature Engineering:** Created new columns for `Order Year` and `Order Month` to facilitate time-series analysis.
4.  **Exploratory Data Analysis (EDA):** Used Pandas to group and aggregate data to answer key business questions about profit, sales trends, and top markets.
5.  **Dashboard Creation:** Connected the cleaned data to Tableau and built worksheets for each key insight. Assembled the final interactive dashboard.

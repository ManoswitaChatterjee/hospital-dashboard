# Hospital-dashboard
It is an Interactive dashboard to help visualize and analyze key hospital performance metrics for data-driven insights and decision making.

### Introduction
A comprehensive dashboard built to analyze and derive insights regarding hospital admission numbers, patient details, and healthcare KPIs using real-world hospital data.

### Goal 
1. To perform data cleaning to ensure data quality and consistency
3. Visualize key hospital metrics such as admissions, discharges, and patient demographics

### About the Dataset
1. All the data used in this dashboard is from the "healthcare_dataset", available in Kaggle (https://www.kaggle.com/datasets/prasad22/healthcare-dataset?resource=download)
3. This dataset contains fictional hospital data hospital data including patient details, admission/discharge dates, department, diagnosis, and billing information.

### KPIs 
1. **Patients -** This KPI represents the total revenue generated from all sales transactions.
   **Formula :** Total Sales = SUM(Sales)
   
2. **Avg. Bill (usd) -** This measures the profitability by comparing profit against sales, indicating how efficiently the business generates profit.
   **Formula:** Profit Margin = SUM(Profit) / SUM(Sales)
   
--------------------------------------------------
### Analysis
The main objective of this report is to nalyze sales performance and profitability trends across the United States.
I specifically choose the above KPIs to help get an overall idea about the ales growth, regional profitability, and customer behaviour from the data. This in turn allows to understand the current standing of the sales and which area needs more focus to help with business growth.

### Overview 

1. Total Sales Count - 2,297,201
2. Profit Margin - 12.47 %
3. Total Orders Count - 9,994
4. Region with Highest Sales - West
5. Customer Return Rate - 2.96 %

![Screenshot_5](https://github.com/user-attachments/assets/ed12f5b0-b574-4910-bfa6-7297ff640528)

#### Insight:
Focus should be on increasing the Profit Margin and lowering the return rate to help with overall business flow.

#### Sales visualization on United States Map with Tooltip

The US map shows distribution of sales across states over the years with a tooltip to easily get details for each state separately.

![Screenshot_6](https://github.com/user-attachments/assets/1dae1d04-e6bd-41eb-8b55-1afc049e334b)

#### Sales monthly growth chart - state-wise 

This table shows sales performance and month-over_month sales growth across each state. It highlights seasonal fluctuations and regional variations, allowing for a detailed comparison of sales growth over time in different states.

![Screenshot_7](https://github.com/user-attachments/assets/35f3b0d1-0bc9-49d1-8bc5-73f740a6adf9)

#### Sales over Time

This line chart illustrates sales trends over time on a monthly basis. It tracks monthly  sales fluctuations within the United States. It reveals patterns in sales growth, highlighting peaks and troughs across different periods, which helps in understanding seasonal demand and overall sales trajectory. 
1. This data shows that there is a surge in sales in the months of November and December for every year from 2014 to 2017.
2. The 'Order Year' filter allows you to check sales details for every year separately to help understand the sales growth over time. 

![Screenshot_8](https://github.com/user-attachments/assets/ad304d72-1c47-4377-9c9a-78d051147b27)

#### Top / Bottom States by sales

These two tables display the top 3 and bottom 3 states in terms of sales performance, providing insights into regional strengths and weaknesses.
1. Top 3 States Table: Highlights the states generating the highest sales, showcasing areas with the strongest performance.
2. Bottom 3 States Table: Identifies the states with the lowest sales, helping to pinpoint regions requiring improvement or further analysis.
3. From our data, the best performing state of all time in terms of sales is California and the worst performing state is North Dakota.

![Screenshot_9](https://github.com/user-attachments/assets/6875351e-16ff-4c2b-bf69-a21a4407c7cb)

### Final Dashboard 

![Screenshot_10](https://github.com/user-attachments/assets/b14082a5-52ec-4fbd-83ad-b8207546dee5)

### Filters 
1. **Order Year -** To filter sales data by specific years, enabling year-over-year comparisons and analysis of long-term trends.
2. **Order Month -** To filter data by month, which helps in examining seasonal sales patterns and monthly performance fluctuations.
3. **Agent Name -** This filters data by sales manager, allowing users to view performance metrics for each manager within their designated region.
4. **Region -** To filter data by major geographical regions, such as East, West, South, and Central, facilitating regional performance analysis.
5. **State -**  This filters data by individual U.S. states, providing a closer look at sales performance at the state level.

### Conclusion 

The USA Sales performance dashboard provided a comprehensive analysis of regional and state-level sales trends using the Sample Superstore dataset. The analysis highlighted key performance metrics and revealed valuable insights into sales growth, profitability, and customer behaviour across the United States.

#### Recommendations and Key Takeaways

1. Top Performing Regions: Regions like the West and Central consistently demonstrated a better sales performance over the years, suggesting strategies in these regions could be replicated elsewhere.
2. Opportunities for Improvement: States with lower sales, identified through the bottom 3 analysis, present opportunities for targeted marketing and sales initiatives to drive growth.
3. Seasonal Trends: Monthly sales trends revealed predictable peaks and troughs. This inturn allows for better capital management and inventory management.
4. Agent Contributions: Insights into sales manager (Agent Name) performance help pinpoint high-performing managers and identify areas where additional support may be needed.

This project helps to visualize data and uncover insights to help make more informed decisions for sales strategy and performance optimization for business.

Your feedback and thoughts on this analysis are greatly appreciated!

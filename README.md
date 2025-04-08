# Adventure Sales Dashboard Project Using Power BI

## Dataset Overview and Problem Statement

This project represents the final work for the "Power Tools For Visualization" course offered by Macquarie University through the Coursera platform. The dataset used is from Adventure, a bicycle company, covering the period between 2017 and 2020. The data was extracted from the original database in the form of 6 raw tables that needed cleaning and modeling. The main objective was to build a comprehensive dashboard consisting of three different control panels to meet specific analytical needs:

* **Sales Analysis Dashboard:** Visualizing sales movement by time periods, countries, states, product categories, and subcategories.
* **Performance Indicators Dashboard:** Tracking monthly sales increases and decreases for each year.
* **Employee Performance Dashboard:** Analyzing sales representatives' contributions to total sales and comparing them with the targets set during the four years.

## Methodology and Applied Skills

### 1. Data Cleaning and Modeling
I cleaned the data using `Power Query` before loading it into `Power BI`, then created an integrated data model by connecting the six tables based on the logical relationships from the original database. This approach ensured data integrity and ease of information extraction.

### 2. Creating a Smart Calendar
I developed a custom time calendar covering the period from July 2017 to July 2020, which facilitated calculations and metrics related to time periods. This calendar enabled advanced analysis based on fiscal year, quarter, and month.

### 3. Developing Advanced Analytical Measures
I used `DAX` language to create a set of advanced metrics and calculations such as:

* Number of items sold (`itemSold`)
* Total orders (`Orders Total`)
* Month-over-Month change (`MoM change`) and percentage change (`MoM % change`)
* Performance comparison with target quotas (`Quota` & `Quota Var`)
* Time metrics (`Fiscal Year`, `Fiscal Month`, `Quarter`, `Month Number`)

### 4. Designing Interactive Dashboards
I designed interactive dashboards that allow users to filter data by various criteria and explore trends and patterns in sales. I used a variety of data visualizations to present information in a clear and useful way.

### 5. Developing a Mobile-Responsive Version
I created a responsive version of the three dashboards specifically designed for display on mobile phones through the `Power BI Mobile` application, ensuring access to important information anytime, anywhere.

## Results and Insights

Through this project, I was able to:

* **Identify Key Sales Trends:** The dashboard revealed clear seasonal patterns in bicycle sales, with peaks at specific times of the year.
* **Improve Visibility Across Geographic Regions:** I identified the highest and lowest performing regions and countries, providing valuable insights for future expansion and resource allocation.
* **Analyze Product Performance:** I identified the most profitable categories and products, helping with strategic decisions regarding product development and inventory.
* **Monitor Sales Team Performance:** I provided insights into the performance of sales employees compared to their set targets, enabling better decisions regarding incentives and training.
* **Develop an Integrated Business Intelligence System:** I created a comprehensive business intelligence solution using `Power BI` that supports data-driven decision making at all levels of the organization.

This final project for the "Power Tools For Visualization" course from Macquarie University demonstrates my ability to apply theoretical concepts in a practical context, and transform raw data into actionable business insights using `Power BI`, focusing on solving real business problems and providing innovative solutions to improve the decision-making process.

# Athletic Sales Data Analysis with Pandas

## Purpose
The **Athletic Sales Data Analysis with Pandas** program is designed to provide insights into product sales, regional performance, and retailer profitability for a fictional athletic footwear company. This project uses Python's Pandas library to explore and analyze sales data, uncovering valuable business insights. By examining sales across various regions, products, and retailers, this analysis highlights key trends and performance metrics that can drive strategic decision-making for businesses.

As a data analyst, I created this project to enhance my skills in working with large datasets and solving real-world business problems using Python. This project simulates a business scenario where data analysis helps identify opportunities for growth, customer preferences, and profitability improvements. It allowed me to apply data transformation, aggregation, and visualization techniques, enhancing my data analysis proficiency.

## Overview
The **Athletic Sales Data Analysis with Pandas** project guides users through the process of exploring, transforming, and analyzing a sales dataset. The goal is to answer critical business questions such as:

- Which regions and retailers generate the highest sales?
- What are the sales trends across different product categories and time periods?
- Which products generate the most profit, and in which regions?
- How do sales methods vary across retailers?

This project provides hands-on experience in manipulating and analyzing data using Pandas, along with visualizing insights through Matplotlib and Seaborn.

## Data Dictionary
The dataset includes the following columns:

| Column          | Data Type  | Description                                                   |
|-----------------|------------|---------------------------------------------------------------|
| retailer        | object     | Name of the retailer                                          |
| retailer_id     | int64      | Unique identifier for each retailer                           |
| invoice_date    | object     | Date when the sale occurred (YYYY-MM-DD format)               |
| region          | object     | Region where the sale was made (e.g., North, South, etc.)     |
| state           | object     | U.S. state where the sale was made                            |
| city            | object     | City where the sale was made                                  |
| product         | object     | Product category (e.g., Women’s Athletic Footwear)            |
| price_per_unit  | int64      | Price per unit of the product                                 |
| units_sold      | int64      | Number of units sold                                          |
| total_sales     | int64      | Total sales amount (units_sold * price_per_unit)              |
| operating_profit| float64    | Operating profit generated from the sale                      |
| sales_method    | object     | Method of sale (e.g., online, in-store)                       |

### Additional Information
- **Row Count**: 9,643 entries
- **Data Types**: Includes object (string), int64 (integer), and float64 (floating-point) data types
- **Memory Usage**: Approximately 1 MB
- **Non-null Count**: All columns have 9,643 non-null entries, indicating no missing data.

## Project Structure
The project is organized into the following directories and files:

- **Data Dictionary/**: Contains a description of the dataset and fields.
- **LICENSE**: The license file for the project.
- **README.md**: This documentation file.
- **Starter_Code/**: Contains the notebook and Python code used for the analysis.
- **Resources/**: Includes the dataset used in the analysis.
- **Visuals/**: Contains PNG files of the visualizations created during the analysis.

## Visualizations
The following visualizations were created to provide insights into the dataset:

- **[Total Sales by Retailer](Visuals/total_sales_by_retailer.png)**: A bar chart illustrating the total sales generated by each retailer.
- **[Top 10 Days with the Most Sales](Visuals/top_10_days_sales.png)**: A bar chart showing the days with the highest athletic footwear sales.
- **[Top 10 Weeks with the Most Sales](Visuals/top_10_weeks_sales.png)**: A bar chart showing the weeks with the highest athletic footwear sales.
- **[Operating Profit by Region](Visuals/operating_profit_by_region.png)**: A bar chart showing the operating profit across different regions.
- **[Price Distribution Across Top 15 Cities](Visuals/price_per_unit_by_city.png)**: A box plot showing the price distribution across the top 15 cities.
- **[Sales Method Distribution by Retailer](Visuals/sales_method_by_retailer.png)**: A count plot showing the distribution of sales methods (online/in-store) by retailer.
- **[Top Products Sold by Retailer](Visuals/top_products_by_retailer.png)**: A bar chart showing the most popular products sold by each retailer.
- **[Monthly Sales Trend by Region](Visuals/sales_trend_by_region.png)**: A line chart illustrating the monthly sales trend by region.

These visuals are located in the **Visuals/** directory and serve as an aid in uncovering trends and patterns within the data.

## Use Cases
The program is designed to answer several key business questions:

- **Regional Sales Analysis**: Determine which regions and cities generate the most sales and operating profit. This information can help businesses focus their efforts on high-performing areas.
- **Retailer Performance**: Identify the top-performing retailers by total sales and product categories. This can guide inventory and marketing decisions.
- **Profitability Analysis**: Calculate operating profit by product and region to identify opportunities for margin improvement.
- **Sales Trend Analysis**: Analyze sales trends over time (daily, weekly, and monthly) to understand peak periods and plan future strategies.

## Technologies Used
- **Python**: The core programming language used for data manipulation and analysis.
- **Pandas**: A powerful data manipulation library used for exploring, transforming, and aggregating data.
- **Matplotlib & Seaborn**: Libraries used for creating visualizations and graphs to present the results of the analysis.
- **Jupyter Notebook**: An interactive coding environment used for conducting and presenting the analysis.
- **Git**: Version control for tracking code changes.
- **GitHub**: Repository hosting platform used for sharing and collaboration.

## Key Features
- **Data Exploration**: The program allows users to explore the dataset, calculate key metrics, and display summary statistics.
- **Data Transformation**: The program performs data transformations such as calculating total sales, profit, and sales trends.
- **Visual Analysis**: Visual representations of the data provide a clear understanding of regional and retailer performance.
- **Profit and Sales Insights**: The analysis identifies the most profitable products and regions, as well as sales trends.

## Usage Instructions
1. **Data Exploration**:
   - Open the Jupyter Notebook in the **Starter_Code/** folder.
   - Load the dataset and explore key statistics using Pandas.
   
2. **Data Transformation**:
   - Calculate total sales, operating profit, and sales trends.
   - Use Pandas to group, aggregate, and summarize the data by region, retailer, and product category.
   
3. **Visualizations**:
   - Create visualizations using Matplotlib and Seaborn to present key findings.

## Recommendations
Based on the analysis, here are some business recommendations:

1. **Focus on High-Performing Retailers**: Prioritize relationships with retailers that generate the most sales.
2. **Capitalize on Peak Sales Days/Weeks**: Identify promotional opportunities during peak periods based on sales trends.
3. **Optimize Inventory for Popular Products**: Use the product sales analysis to adjust inventory levels and ensure stock availability for high-demand products.
4. **Regional Targeting**: Focus on regions and cities that show the highest sales and profitability, and consider expanding into nearby areas.

## Conclusion
The **Athletic Sales Data Analysis with Pandas** project provides a comprehensive look at sales performance across regions, retailers, and products. By focusing on key metrics like total sales, operating profit, and sales trends, businesses can make data-driven decisions to optimize their operations and improve profitability.

The visualizations and analyses presented in this project highlight the importance of understanding regional sales trends, retailer performance, and product profitability. These insights enable businesses to tailor their strategies and maximize their impact.

This project has also enhanced my understanding of data analysis techniques and how they can be applied to real-world business scenarios using Python and Pandas.

## References

Sales Product Data. Available: [https://www.kaggle.com/datasets/knightbearr/sales-product-data](https://www.kaggle.com/datasets/knightbearr/sales-product-data)

The sales product data above was modified by edX Boot Camps LLC, and is intended for educational purposes only.

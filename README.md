# Athletic Sales Data Analysis with Pandas

## Purpose
The **Athletic Sales Data Analysis with Pandas** program provides insights into product sales, regional performance, and retailer profitability for a fictional athletic footwear company. This project uses Python's Pandas library to explore and analyze sales data, highlighting key trends and metrics to aid business decision-making.

As a data analyst, I developed this project to enhance my skills in working with large datasets and solving real-world business problems. The project simulates a business scenario, allowing me to apply data transformation, aggregation, and visualization techniques using Python.

## Overview
The **Athletic Sales Data Analysis with Pandas** project addresses key business questions:

- Which regions and retailers generate the highest sales?
- What are the sales trends across product categories and time periods?
- Which products are most profitable, and in which regions?
- How do sales methods vary across retailers?

This project demonstrates the use of Pandas for data manipulation and Matplotlib/Seaborn for visualizations.

## Data Dictionary
The dataset contains the following columns:

| Column          | Data Type  | Description                                                   |
|-----------------|------------|---------------------------------------------------------------|
| retailer        | object     | Name of the retailer                                          |
| retailer_id     | int64      | Unique identifier for each retailer                           |
| invoice_date    | object     | Date of the sale (YYYY-MM-DD)                                 |
| region          | object     | Region where the sale occurred                                |
| state           | object     | U.S. state of the sale                                        |
| city            | object     | City where the sale occurred                                  |
| product         | object     | Product category (e.g., Women’s Athletic Footwear)            |
| price_per_unit  | int64      | Price per unit of the product                                 |
| units_sold      | int64      | Number of units sold                                          |
| total_sales     | int64      | Total sales (units_sold * price_per_unit)                     |
| operating_profit| float64    | Operating profit generated from the sale                      |
| sales_method    | object     | Method of sale (e.g., online, in-store)                       |

### Dataset Summary
- **Row Count**: 9,643 entries
- **Memory Usage**: 1 MB
- **Non-null Count**: All columns have 9,643 non-null entries
- **Data Types**: A mix of object (string), int64 (integer), and float64 (floating-point)

## Project Structure
The project includes the following:

- **Resources/**: Contains the sales datasets (`athletic_sales_2020.csv` and `athletic_sales_2021.csv`).
- **Starter_Code/**: Contains the analysis notebook and code (`athletic_sales_analysis.ipynb`).
- **Visuals/**: Includes all visualizations created during the analysis.
- **README.md**: This documentation file.

## Visualizations
The project generated the following visualizations to provide insights:

1. **[Top 10 Days with the Most Sales](Visuals/top_10_days_sales.png)**: Bar plot showing the days with the highest women's athletic footwear sales.
2. **[Top 10 Weeks with the Most Sales](Visuals/top_10_weeks_sales.png)**: Bar plot showing the weeks with the highest sales.
3. **[Monthly Sales Trend](Visuals/monthly_sales_trend.png)**: Line plot showing the monthly sales trend.
4. **[Total Sales by Retailer](Visuals/total_sales_by_retailer.png)**: Bar plot showing total sales by retailer.
5. **[Sales Method Distribution by Retailer](Visuals/sales_method_by_retailer.png)**: Count plot showing the distribution of online and in-store sales.
6. **[Operating Profit by Region](Visuals/operating_profit_by_region.png)**: Bar plot showing operating profit across regions.
7. **[Price per Unit Distribution Across Top 15 Cities](Visuals/price_per_unit_by_city.png)**: Box plot showing the price distribution across the top 15 cities.
8. **[Top Products Sold by Retailer](Visuals/top_products_by_retailer.png)**: Bar plot showing the top-selling products by retailer.
9. **[Sales Trend by Region](Visuals/sales_trend_by_region.png)**: Line plot illustrating the monthly sales trend by region.
10. **[Total Sales Over Time (Daily)](Visuals/total_sales_daily.png)**: Line plot showing the total daily sales.
11. **[Heatmap of Sales by Region and Product](Visuals/sales_heatmap_region_product.png)**: Heatmap showing total sales by region and product.
12. **[Units Sold Distribution by Region](Visuals/units_sold_by_region.png)**: Box plot showing the distribution of units sold across regions.
13. **[Total Sales by Product Category Over Time](Visuals/total_sales_by_product_over_time.png)**: Line plot showing monthly sales by product category.
14. **[Correlation Heatmap for Numeric Variables](Visuals/correlation_heatmap.png)**: Heatmap showing the correlation between numeric variables.

## Use Cases
The analysis addresses key business questions:

1. **Regional Performance**: Identifies which regions and cities generate the highest sales and operating profit.
2. **Retailer Insights**: Highlights the performance of top retailers.
3. **Profitability**: Evaluates operating profit by product and region.
4. **Sales Trends**: Analyzes sales trends to identify peak sales periods and inform future strategies.

## Technologies Used
- **Python**: For data manipulation and analysis.
- **Pandas**: For data exploration, transformation, and aggregation.
- **Matplotlib & Seaborn**: For creating visualizations.
- **Jupyter Notebook**: For conducting and presenting the analysis.
- **Git/GitHub**: For version control and sharing the project.

## Recommendations
The analysis reveals several recommendations:

1. **Focus on High-Performing Regions**: Invest in regions with strong sales performance.
2. **Promote Popular Products**: Optimize inventory and promotions around top-selling products.
3. **Leverage Sales Trends**: Use peak sales periods to drive promotions and campaigns.
4. **Improve Profit Margins**: Target regions and products where profitability can be improved.

## Conclusion
The **Athletic Sales Data Analysis** project demonstrates the power of data analysis for driving business decisions. By analyzing sales data across regions, products, and retailers, the project identifies key performance metrics and trends that inform strategic planning. This project enhanced my ability to manipulate, analyze, and visualize large datasets using Python, Pandas, and data visualization libraries.

## References

Sales Product Data: [Kaggle Dataset](https://www.kaggle.com/datasets/knightbearr/sales-product-data)

The sales product data was modified by edX Boot Camps LLC, and is intended for educational purposes only.


Coffee Shop Sales Performance Dashboard
Project Overview:
This project analyzes coffee shop sales data to understand product performance, store performance, transaction patterns, and sales trends.
Using Power BI and Power Query, I cleaned and transformed the dataset, created calculated fields, and developed an interactive dashboard to identify high-performing products, categories, and store locations.
The analysis focuses on:
- Product category and product type performance
- Store location performance
- Average transaction value
- Transaction quantity
- Sales performance across stores and products
- Transaction patterns by hour
The project was created as part of my practical data analytics portfolio to strengthen my skills in data cleaning, analysis, visualization, and business insight generation.

Tools & Technologies
- Power BI — Dashboard development, data analysis, and visualization
- Power Query — Data cleaning and transformation
- Microsoft Excel — Data source and initial data preparation
Dataset
The dataset contains coffee shop transaction records, including:
- Transaction ID
- Transaction Date
- Transaction Time
- Transaction Quantity
- Store ID
- Store Location
- Product ID
- Unit Price
- Product Category
- Product Type
- Product Details
Additional calculated fields were created during the analysis, including:
- Total Sales = Transaction Quantity × Unit Price
- Transaction Hour — extracted from Transaction Time
The dataset was obtained from Maven Analytics and used for learning and portfolio development.

Data Cleaning & Transformation
The dataset was prepared in Power Query before building the dashboard.
Key steps included:
- Checked column quality to confirm valid data and identify potential errors or missing values.
- Checked the Transaction ID column for duplicate records.
- Reviewed product categories and product types for consistency.
- Created a Total Sales calculated column by multiplying Transaction Quantity by Unit Price.
- Extracted Transaction Hour from Transaction Time to analyze transaction patterns throughout the day.
- Reviewed the available date fields and identified limitations in the Transaction Date data before using it for analysis.
- Confirmed appropriate data types for numerical and time-based fields.
- Loaded the cleaned and transformed data into Power BI for analysis and visualization.

  Dashboard Analysis
The Power BI dashboard was designed to provide an overview of sales performance across products and store locations.
The dashboard includes eight key analyses:
1. Average Sales by Product Category — compares the average sales performance across product categories.
2. Quantity Sold by Product Category — identifies which product categories have the highest sales quantities.
3. Sales by Product Type — compares total sales across individual product types.
4. Sales by Product Category & Store Location — examines how product category sales vary across store locations.
5. Sales by Store Location & Product Type — compares product type performance across different stores.
6. Average Transaction Value by Store Location — compares the average value of transactions across store locations.
7. Sales by Product Type & Store Location — identifies the strongest product types within each store location.
8. Transaction Quantity by Hour — analyzes transaction quantities across different hours of the day.

   Key Insights
The analysis produced several key findings:
- Coffee was the leading product category by both transaction quantity and total sales.
- Hell's Kitchen generated the highest overall sales among the three store locations analyzed.
- Lower Manhattan had the highest average transaction value, indicating that customers at this location tended to generate higher-value transactions on average.
- Astoria performed strongly across several product types, including Brewed Chai Tea, Hot Chocolate, and Gourmet Brewed Coffee.
- Barista Espresso was the strongest product type overall and performed particularly well in Hell's Kitchen.
- Transaction activity varied by hour, with higher transaction quantities around 10 AM and lower activity during some later hours.

  Recommendations
Based on the analysis, the following actions could help improve sales performance:
- Prioritize high-performing coffee products by maintaining consistent stock availability and visibility.
- Investigate the factors behind Lower Manhattan's higher average transaction value and identify practices that could be applied to other locations.
- Build on Astoria's strong performance in selected product types, particularly Brewed Chai Tea, Hot Chocolate, and Gourmet Brewed Coffee.
- Use Hell's Kitchen as a benchmark for high-performing products, particularly Barista Espresso.
- Review lower-performing products and locations to identify opportunities related to product mix, pricing, promotions, and customer demand.
- Use transaction-hour patterns to support staffing and stock planning, with greater attention to periods of higher transaction activity.

Project Files
The repository contains the following project resources:
- Coffee Shop Sales Performance Dashboard.pbix — Power BI project file containing the data model, transformations, visuals, and dashboard.
- Coffee Shop Sales Performance Dashboard.pdf — PDF version of the completed dashboard for easy viewing.
- Coffee Shop Sales Dataset.zip — Compressed source dataset used for the analysis.
- README.md — Documentation explaining the project, methodology, insights, and recommendations.

  Conclusion
This project provided practical experience in transforming raw sales data into meaningful business insights using Power Query and Power BI.
  The analysis demonstrates how sales data can be used to evaluate product performance, compare store locations, understand transaction patterns, and support data-driven business decisions.  
This project is part of my ongoing data analytics portfolio and reflects my practical approach to data cleaning, analysis, visualization, and business reporting.
  

Project Overview
This project focuses on analyzing sales data from a superstore to identify trends, patterns, and potential issues. The analysis is divided into two main sections:

Exploratory Data Analysis (EDA): Understanding the overall sales performance and trends.
Shipping Delay Analysis: Investigating the problem of shipping delays, identifying root causes, and suggesting actionable insights.
Objectives
To explore and analyze sales data to uncover key business insights.
To examine shipping delays, understand their impact, and propose recommendations for improvement.
Dataset Information
The dataset includes the following columns:

Order Information: Order ID, Order Date, Ship Date, Ship Mode
Customer Information: Customer ID, Customer Name, Segment, Region
Location Details: Country, City, State, Postal Code
Product Details: Product ID, Category, Sub-Category, Product Name
Sales Information: Sales
Tools and Libraries Used
Python Libraries: Pandas, Matplotlib, Seaborn, NumPy
Software: Jupyter Notebook for coding and analysis
Analysis Workflow
1. Data Cleaning
Handling missing values and duplicates.
Formatting date columns (Order Date, Ship Date).
Creating new columns:
Order Month: Extracting the month from the order date.
Shipping Delay: Classifying orders as delayed if the shipping duration exceeds the mode of shipping duration for the respective shipping mode.
2. Exploratory Data Analysis (EDA)
Sales Trends: Monthly and yearly analysis of sales.
Regional Analysis: Examining sales performance by region, state, and city.
Category Analysis: Identifying top-performing categories and subcategories.
3. Shipping Delay Analysis
Calculating the mode of shipping duration for each shipping mode.
Investigating delays by month and region.
Highlighting months with the highest average shipping delays (e.g., August and December).
Analyzing the impact of delays on customer segments and regions.
4. Insights and Recommendations
Key findings from sales and delay analyses.
Suggested strategies to improve shipping efficiency and sales performance.
Results and Visualizations
Visualizations include line charts, bar plots, and heatmaps to showcase trends and patterns.
Comparative analysis of shipping delays by month, mode, and region.
Usage Instructions
Clone or download this repository.
Open the Jupyter Notebook file in your environment.
Ensure all required Python libraries are installed.
Run the code cells sequentially to perform the analysis.
Key Findings
The highest sales occur in specific months and regions, suggesting seasonal and regional factors.
Shipping delays are most prominent in August and December, impacting customer satisfaction.
Strategies such as optimizing shipping routes and addressing high-demand periods can reduce delays.
Files Included
superstore_sales_Fina.ipynb: The Jupyter Notebook containing the full analysis.
superstore sales dataset.csv: The dataset used for this analysis.
project_document.pdf: Detailed project documentation including findings and recommendations.
Contact
For further questions or collaboration, please contact:
Roaa
Email: [roaam6554@gmail.com]

# Amazon-Sales-Analysis

## Introduction
The "Amazon Sales Analysis" project is a data analysis initiative that aims to explore and understand sales data from Amazon. Using Python libraries such as NumPy, Pandas, Matplotlib, and Seaborn, this project focuses on analyzing and visualizing the dataset.

## Data Loading and Inspection
We begin by loading the sales data from a CSV file with Pandas. The dataset contains 128,976 entries and 21 columns, including Order ID, Date, Status, Sales Channel, Quantity, and Amount. Initial inspection methods like head(), info(), and shape provide an overview of the data structure.

## Data Cleaning
To improve the dataset's usability, we perform several cleaning steps. Unrelated or blank columns, such as 'New' and 'PendingS', are removed. We handle null values by either dropping affected rows or filling in missing information. Additionally, we adjust data types for consistency, converting columns like 'Date' into datetime objects for better analysis.

## Exploratory Data Analysis (EDA)
### 1. Size Analysis
Count plots reveal the distribution of purchases by size, indicating that M-Size is the most popular among buyers.

### 2. Grouping by Size
By grouping the data by size, we gain insights into the quantity of products sold for each size, confirming that M-Size products lead in sales.

### 3. Courier Status and Order Status
Count plots analyzing shipping methods and order statuses show that most orders are shipped via couriers.

### 4. Category Distribution
A histogram visualizes the purchase distribution across different product categories, highlighting T-shirts as the most frequently bought items.

### 5. B2B Analysis
A pie chart displays the distribution between Business-to-Business (B2B) and retailer buyers, revealing that 99.3% of buyers are retailers.

### 6. Fulfilment Analysis
A pie chart illustrates the distribution of fulfilment methods, with Amazon being the primary fulfilment service.

### 7. Scatter Plot and State-wise Distribution
Scatter plots are used to explore relationships between product categories and sizes. Additionally, state-wise distribution plots provide insights into the geographical concentration of buyers, with Maharashtra having the highest number of customers.

## Clustering 
To further analyze customer behavior and segment the data, we apply clustering techniques. By using methods like K-means clustering, we identify distinct customer segments based on purchasing patterns, such as quantity and category preferences. This segmentation helps in understanding the different groups within the customer base, allowing for more targeted marketing strategies.

## Prediction Model
We implement a Random Forest prediction model to forecast future sales trends based on historical data. This model analyzes various factors, including product categories, sizes, and sales channels, to make predictions about future sales performance. The Random Forest approach enhances accuracy by utilizing multiple decision trees and averaging their results, providing robust predictions that can aid in inventory management and strategic planning.

## Conclusion
The Amazon Sales Analysis project offers valuable insights into customer preferences, popular product categories, and geographic distribution. The inclusion of clustering and a Random Forest prediction model further enhances the analysis, allowing businesses to make informed decisions, optimize inventory, and improve customer satisfaction.

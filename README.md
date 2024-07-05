**Exploratory Data Analysis on E-Commerce Data**

📕This repository contains an exploratory data analysis (EDA) on a comprehensive e-commerce dataset from the Brazilian e-commerce platform Olist. The analysis aims to uncover insights into customer behavior, sales trends, payment methods, and geographic distributions.

📃Purpose
The primary goal of this project is to perform a thorough analysis of e-commerce data to:

Understand customer demographics and purchasing patterns.
Identify sales trends and seasonal variations.
Analyze payment methods and their impact on sales.
Explore geographic distributions of customers and sellers.
Contents

📚Notebooks:
E-Commerce_Data.ipynb: Main Jupyter notebook for EDA, containing all analyses and visualizations.

🗒Data:
olist_customers_dataset.csv
olist_geolocation_dataset.csv
olist_order_items_dataset.csv
olist_order_payments_dataset.csv
olist_order_reviews_dataset.csv
olist_orders_dataset.csv
olist_products_dataset.csv
olist_sellers_dataset.csv
product_category_name_translation.csv

🎨Visualizations:
Various .png images showing insights like sales trends, order statuses, and geographic distributions.
Highlights
Customer Analysis: Distribution of customer counts by cities and states, analysis of customer demographics.
![Distribution of Customer Count by Cities](https://github.com/selinolgun/Exploratory-Data-Analysis-on-E-Commerce-Data/assets/126022358/e09f9694-90d0-4c1f-b4bc-f2a77d46905a)

Sales Trends: Monthly sales trends, seasonal sales patterns, and product category analysis.
![Seasonal Sales](https://github.com/selinolgun/Exploratory-Data-Analysis-on-E-Commerce-Data/assets/126022358/995107ba-2b5c-4efc-afa2-ace3273cf773)

Payment Analysis: Analysis of different payment types, payment values, and their distribution.
![The Effect of Number of Installments on Payment Value](https://github.com/selinolgun/Exploratory-Data-Analysis-on-E-Commerce-Data/assets/126022358/3db97839-4e58-408c-96df-999f4e4ba7dc)

Geolocation Insights: Geographic distribution of sellers, order density by location, and delivery times.
![Correlation between Geolocation and Delivery Times](https://github.com/selinolgun/Exploratory-Data-Analysis-on-E-Commerce-Data/assets/126022358/56842745-56ae-4924-a9bc-9b537d9589ee)

🔍Usage:
git clone https://github.com/selinolgun/Exploratory-Data-Analysis-on-E-Commerce-Data.git

📉Navigate to the Directory:
cd Exploratory-Data-Analysis-on-E-Commerce-Data

📏Explore the Jupyter Notebook:
Open E-Commerce_Data.ipynb to view the complete analysis and visualizations.

🖋Dependencies
Python 3.7+
Jupyter Notebook
Pandas
Matplotlib
Seaborn
Geopandas (for geographic data analysis)
Install the required packages using:
pip install -r requirements.txt
Acknowledgements
This project utilizes data from the Brazilian e-commerce platform Olist. Special thanks to Olist for providing this dataset for public analysis.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

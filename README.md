# Laptop Price Analysis

## Project Overview
This project analyzes laptop prices based on various factors such as brand, processor type, RAM, storage, and other specifications. The dataset is cleaned, processed, and visualized to derive meaningful insights. The goal is to identify key factors affecting laptop prices

## Tools and Libraries
- Python: Data analysis and processing
- Pandas & NumPy: Data manipulation
- Matplotlib & Seaborn: Data visualization
- Plotly: Interactive charts

## Data Cleaning And Preparation
- Dropeed Unnecessary Columns : Removed ‘Laptop ID’ and ‘Product’ as they were not useful for analysis.
- Handled missing values: Checked and ensured no critical missing data.
- Removed duplicates: Eliminated redundant entries to improve data integrity.
- Transformed numerical data: Converted RAM and Weight to numeric formats.
- Converted currency: Prices were initially in Euros and converted to INR using an exchange rate of 89.07.

## Project Insights
1. RAM prices show significant jumps from low capacity (2-6GB) to high capacity (24-64GB), with the most balanced price-to-capacity ratio found in the mid-range (8-16GB) segment.
2.  heavier Laptops generally have higher prices.
3.  Apple and MSI have the highest average prices, while Acer is the lowest. Price variance is highest for Apple and MSI, indicating a mix of budget and premium models, whereas Acer has the most consistent pricing. Mid-range brands like HP, Dell, Lenovo, Asus, and Toshiba show moderate price stability, appealing to balanced consumer segments.
4.  Workstations and gaming laptops have the highest prices, while notebooks and netbooks are the most affordable.
5.  15.6-inch laptops dominate the market, significantly outnumbering other sizes. Smaller screen sizes (12.5" and 11.6") have the least representation, indicating lower demand or availability.
6. The bar plot shows that AMD Ryzen series, Intel Core i7, and Intel Core i5 have the highest prices, indicating these processors are likely targeting the high-performance or gaming market.
7. Nvidia Quadro, Intel Iris, and AMD FirePro GPUs have the highest prices, suggesting they are tailored for professional, high-end applications such as graphics design, video editing, and AI processing.

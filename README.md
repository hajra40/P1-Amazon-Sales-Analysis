# P1 Amazon Sales Analysis

In this project, the data of amazon sales sourced from kaggle is comprehensively analysed using various functions and charts. The dataset provides valuable insights into sales trends, customer behavior, and product performance across various categories.

Link: https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset

## Objectives

1. **Data Exploration:** To understand the structure and key features of the dataset.
2. **Sales Trends:** To analyze sales performance over time and identify seasonal patterns.
3. **Product Performance:** To evaluate which products are driving sales and which categories are underperforming.

## Data Exploration

This dataset is having the data of 1K+ Amazon Product's Ratings and Reviews as per their details listed on the official website of Amazon. The following are the features of the data:
* product_id - Product ID
* product_name - Name of the Product
* category - Category of the Product
* discounted_price - Discounted Price of the Product
* actual_price - Actual Price of the Product
* discount_percentage - Percentage of Discount for the Product
* rating - Rating of the Product
* rating_count - Number of people who voted for the Amazon rating
* about_product - Description about the Product
* user_id - ID of the user who wrote review for the Product
* user_name - Name of the user who wrote review for the Product
* review_id - ID of the user review
* review_title - Short review
* review_content - Long review
* img_link - Image Link of the Product
* product_link - Official Website Link of the Product

The category column is in the form of breadcrumb i.e. current category within navigational hierarchy and the exact category can be extracted using the trim function. Next, the data was cleaned, null and duplicate values were removed, and the columns were formatted. The data wa stored as a table "sales".

![Screenshot 2024-09-23 221548](https://github.com/user-attachments/assets/dc6edb39-8574-41d7-a4c2-a80715adc141)

## Dashboard Insights - Sales Trend, Top Products and Categories, Top Rated Categoies

1. Total Amount Earned - 4.579 Million Rupees
2. Total Users of Amazon - 1465
3. Top 5 products - Fire Blott Ninja Call, Fire Blott Phoenix Smart Watch, Wayona Nylon Braided USB to Lighting Fast Charging, Sounce Fast Phone Charging Cable, Portronics Connect
4. Top 5 products by category - USBCables, SmartWatches, SnartPhones, SmartTelevision, In-Ear
5. Top 15 Highly Rated Catgeories

![Screenshot 2024-09-18 212838](https://github.com/user-attachments/assets/3e7a63b9-b3ad-42b8-971a-65f2580d08b3)



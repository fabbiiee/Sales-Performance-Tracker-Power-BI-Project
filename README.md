# Sales-Performance-Tracker-Power-BI-Project
A Power BI dashboard built using SQL-cleaned data to track sales trends, top products, regions, and customer performance. Helps drive smarter decisions and boost revenue through clear, interactive insights.

### Overview:
This Project was designed to help the company to be able to monitor and analyze key metrics across customers, products, regions, sales, orders and time. Its main purpose is to provide clear insights into sales trends, performance, opportunities for growth and having a clear idea on how to fix up the lapses. By consolidating data into a visual and interactive format, Business leaders, sales teams stand a better chance of making informed decisions, optimize strategies and drive revenue growth.

### Data Source:
The dataset of this project was sourced from `Kaggle.com`, exported in CSV format. It includes transactional records spanning from January 2003 to September 2004, capturing detailed sales activity across multiple regions and product categories. The key variables of the dataset include order number, quantity ordered, price, sales, order date, status, product line, customer name, phone number, address, city, postal code, country, customer name and deal size.

### Tools used:
I made use of SQL first, which I used extract, manipulate and analyze the data. I used SQL because of how large the dataset was. Then, I used Power BI for the visualization.

### Data cleaning:
I achieved this using SQL, the first step I took was to create a duplicate of the dataset for error recovery, then I removed the duplicates which I achieved by creating temporary row numbers and deleting the duplicate rows. I standardized some of the data that needed to be standardized using the TRIM function and also changed the data type of the date column. There were no much missing values, but the few missing values were as a result of the customers not providing some of the optional data like their second addresses and their states. But this was not an issue because the important data were complete.  

### Analysis techniques: 
I used the filters to segment sales by products, regions, time. I summed the total sales, the average price of products, the total orders made and the total product quantities ordered to track performances. I evaluated monthly and yearly sales patterns to identify seasonality. I identified the top customers, products and regions by sales and orders.

#### Visualizations used:
I used mainly Bar charts, Tables and KPI cards for simplicity and easy understanding. I also used slicers for easy interaction and dynamism.
Challenges and learnings: There is a popular quote that says “Challenges help you learn”. I encountered little challenges working on this project because the dataset was not so dirty. I had challenges trying to change the data type of the date column in SQL, but I later learned that the problem was from the dataset itself. So I had to change it using the power query editor on Power BI which made it far more easier for me. My lesson from the whole challenge is to always work with a data analysis tool that makes my work easier and faster for me.

#### Dashboard:
![Sales Performance Tracker Dashboard Page 1](https://github.com/user-attachments/assets/f74fc235-33ef-4c0b-b8d5-bc33b47fa3c0)
![Sales Performance Tracker Dashboard Page 2](https://github.com/user-attachments/assets/23ef7c37-714e-406d-8bac-5563bccfa3e3)
![Sales Performance Tracker Dashboard Page 3](https://github.com/user-attachments/assets/6e25c11f-9497-4356-995f-79de9a1590f5)




### Conclusion: 
This analysis provided valuable insights into Sales performance across customers, products and regions. Through data cleaning, aggregation and visualization, I identified key trends, high performing areas and areas for improvement. By acting on the recommendations like focusing on the top products and addressing regional gaps, the organization can improve revenue performance and make informed decisions moving forward.
I would also like to recommend you to continue tracking the KPIs(key performance indicators) using the dynamic dashboard I created and update the dataset regularly to monitor changes.


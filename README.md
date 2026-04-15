# Coffee Sales Analysis
### 1. Objective 
This project aims to analyze sales of coffee products of a cafe to determine sales increase over 2 years span (2024, 2025), determine high-demand products, rush hours, and come up with a strategy to further increase sales and consumer satisfaction.

### 2. Dataset 
•	Source: Kaggle (Coffee Sales Dataset) 
•	Contains information on order date (hour, weekday, month,...), time, payment method, and sales amount. 
•	Compromised of about 3,500 transaction records.

### 3. Tools & Technologies 
•	Power Query (Data cleaning) 
•	DAX (Data modelling and summarization)
•	Power BI (Data visualization) 

### 4. Data Cleaning 
•	Removed missing and duplicate records 
•	Standardized column names and data types. 
•	Created DAX measures such as Profit and Revenue 

### 5. Data Modeling 
The data was structured using a star schema, with a FactSales fact table connected to a date dimension table. 

### 6. Business Questions 
•	What are the overall sales over time? 
•	Which drinks provide the highest and lowest sales? 
•	Which drinks are the most and least ordered?
•	What are the rush hour periods throughout the day?
•	Are there seasonal changes in customers’ ordering behavior?

### 7. Analysis 
•	Analyzed monthly sales trends to identify growth and decline periods 
•	Compared different drinks based on sales contribution and quantity sold. 
•	Explored seasonal variations in ordering behavior.

### 8. Visualization 
Dashboard One: Coffee Sales
This dashboard aims to analyze sales trend over time, sales and orders contribution of different drinks, and order frequency changes throughout the day. It contains the following KPIs: total sales, orders, and average order value. It visualizes sales trends over time, orders by daytime, drinks contribution to sales and orders, and compares yearly sales. It helps in determining highly demanded drinks, rush hours, and seasonal sales peaks.
 
### 9. Key Findings (Insights) & Recommendations 
1.	The sales achieved in 2025 are much less than 2024, but we are only through the first quarter of 2025, thus there is no point of comparison in the meantime.
2.	Orders and sales increase throughout February, March, Sep, Oct, and Nov (1st and 4th quarters of the year, specifically). 
3.	More orders come in the late morning (11 AM) and afternoon period (4 PM). The café must make sure of staff and drinks availability throughout these periods urgently.
4.	Generally, demand slightly decreases at nighttime. Accordingly, perishable ingredients redundancy should be adjusted to avoid ingredient wastage. 
5.	Latte and americano with milk are the drinks with highest sales, while cortado and espresso had the least sales. Some drinks, especially caffeinated ones such as americano and americano with milk are mostly demanded in the morning. On the other hand, soothing drinks such as hot chocolate, cocoa, and cappuccino are mostly ordered during the night. Ingredients redundancy should be adjusted accordingly.

# Super Store Sales 

### Project Overview

This report provides an analysis of the dashboard created for sales and business performance evaluation. The dashboard offers key insights into Performance overview of superstore, Segments behavior, Discount impact performance, Sub-categories & Ship-mode performance and regional sales. By using interactive visualizations, the dashboard helps stakeholders make data-driven decisions. This report outlines the objectives, methodology, findings, and recommendations derived from the dashboard analysis.

### Data Source
- The Sample Superstore dataset was collected from kaggle. [Download_Here](https://tinyurl.com/359rzp3c)

### Tools
- Microsoft Excel for Data Cleaning
- Microsoft PowerBi for Data Visualization


### Data Cleaning & Preparation

The Sample Superstore dataset was collected from kaggle. Data preprocessing was done using Microsoft Excel by adding a random date column since the dataset lacked a date column, using the function (“=randbetween(date(2021,1,1), date(2023,12,31)”) and using Power Query to clean and structure the data into eight (8) tables. DAX measures were implemented in Power BI to calculate key performance indicators, including revenue, profit margin, discount amount, and loss percentage.


### Data Modeling

After ensuring my data’s accuracy and consistency, I began the process of creating a data model for my tables. I first establish my data table which is “sales table” then started creating relationships between tables. For this project, I used “one to many” relationship. Screenshot of the completed model is attached below.

![modeling](https://github.com/user-attachments/assets/6bc07569-f08b-401e-b999-8fe92b1b569e)

### DAX Function 

With the table relationships established, I utilized some DAX functions to analyze the dataset. I started by creating basic KPIs such as Revenue, Profit, Orders and Quantity which would help in creating more advanced metrics later on. Some DAX functions I used the most are:
- Iterators Function(SUMX): This formula evaluates an expression based on each row and then aggregates the results.
- Calculate(): Acts as an overriding filter to give you a new filter context.
- Date Function(DateAdd): This date function is very helpful in establishing previous months Orders, Profits and Revenue.

### Dashboard Structure
The dashboard consists of the following key sections:
- Performance Overview Dashboard – Provides insights into revenue trends and profitability trends, orders by categories and relevant KPIs.
  
![image](https://github.com/user-attachments/assets/b6af0104-51cb-4315-a3d5-8bf1c0f5ce47)

- Segment Dashboard – This analyzes the pattern in which each segment places order, their percentage contribution in the discount amount used and the revenue made per Segments. This dashboard contains a slicer filtered by each segment.

![image](https://github.com/user-attachments/assets/95f39f43-e601-4803-8a3e-ac4fe6de59e4)

- Discount Impact Dashboard - This evaluates the discount distribution and the impact of discount on revenue, profit and loss with a category slicer and relevant KPIs.

![image](https://github.com/user-attachments/assets/fd1f68f8-5fd3-4695-9877-32d5a194967b)

- Sub-Categories & Ship-Mode Dashboard – It evaluates ship-modes contribution to all orders, sub-categories sales, and profit margin for each sub-category. This dashboard contains a slicer filtered by each Ship-Mode with relevant KPIs.

![image](https://github.com/user-attachments/assets/2c53d0f5-3b53-4657-8b63-f6a30503c4c9)

- Regional Sales Dashboard - Compares revenue, profit, orders performance across different locations.

![image](https://github.com/user-attachments/assets/6f6d65da-fab5-49a5-8920-c23964b9bdd6)



### Key Findings & Insights
The analysis of the dashboard revealed the following insights:

- Performance Overview – Revenue shows steady growth over time but profit fluctuates with noticeable peaks and drops. Revenue increased 1.08% from the previous month, while profit decreased by 8.11% from the previous month. The impact of discount on profit increased 107% which therefore reduced the profit margin. Looking at the category performance, office supplies lead in the order volume, with an order of over 6,000.
  
- Segment Analysis – Consumer segment drives the highest revenue ($5.8M) but relies heavily on discounts (51.47%), which may impact profitability. Corporate segment ($3.3M revenue) uses fewer discounts (27.8%), making it a more profitable segment. Home Office segment lags in both revenue ($1.1M) and order volume, indicating potential for targeted growth strategies. Order trends show consistent growth in the Consumer segment, while Corporate and Home Office segments have lower but steady orders.

- Discount Impact - High Discount Rates Correlate with Lower Revenue and Profitability. The discount impact on revenue chart shows that as discounts increase, revenue tends to decline. The discount impact on profit chart indicates that higher discounts reduce profitability significantly. Loss Increases with Higher Discounts. The discount impact on loss chart shows a positive trend, meaning that as discounts rise, losses also increase. The loss margin is 6.8%, which indicates a significant portion of sales may be unprofitable due to excessive discounting.

- Sub-category & Ship-Mode - Standard Class Dominates Sales. The Ship Mode % Contribution in Orders chart shows that Standard Class has the highest share of orders (59.69%). Other shipping modes like First Class (19.74%) and Second Class (15.44%) have significantly lower order contributions. Higher Sales Linked to Standard Class, the Ship Mode Linked with Higher Sales chart confirms that Standard Class generates the highest revenue ($6.87M) compared to Second Class ($2.38M) and First Class ($1.62M). Same-day shipping has the lowest sales impact. Sub-Category Sales & Profitability Vary, the Sub-Categories by Sales chart shows that Binders, Paper, and Furnishings are the top-selling categories. The Profit Margin by Sub-Categories chart reveals that Labels (44.41%), Paper (43.14%), and Envelopes (41.46%) have the highest profit margins. Categories like Machines (17.98%) and Furnishings (20.52%) have lower margins, indicating they contribute more to revenue than profitability.

- Regional Analysis - The map visual presents Revenue, Profit, Quantity, and Orders by Cities, segmented into Central, East, South, and West regions.
Cities are represented with different-sized markers, likely indicating variations in sales volume and profitability. Larger markers in cities like New York, Los Angeles, Chicago, and Houston suggest higher sales activity. Regional Focus Areas. The East and West regions seem to have a higher concentration of active cities, possibly contributing more to overall revenue. The South and Central regions might have fewer high-revenue cities, suggesting potential for targeted growth efforts.




### RECOMMENDATIONS
Based on the dashboard insights, the following actions are recommended:

- Reduce discounts on low-margin products to improve profitability.
- Focus marketing efforts on high-performing regions to maximize sales growth.
- Optimize inventory management to prevent overstocking of low-demand products.
- Enhance customer engagement strategies to increase repeat purchases.



### CONCLUSION
The dashboard analysis provides valuable insights into sales, customer behavior, and regional performance. By implementing the recommended strategies, the business can enhance profitability, improve operational efficiency, and make informed decisions based on data-driven insights.


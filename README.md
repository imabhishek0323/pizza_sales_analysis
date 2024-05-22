### ✤ Introduction
I examined a dataset for a fictional pizza business that Analytics provided for this project. Orders, varieties of pizza, and pizza metadata are all included in the dataset. The analysis aimed to offer insights and suggestions to the restaurant’s management so they could make well-informed decisions about running the business. I specifically set out to address four key questions about sales revenue, menu optimization, pizza orders, and customer traffic.

### ✤ The SQL codes for the project 
For this project, I sourced pizza sales data, which contains four csv files: order_details.csv, orders.csv, pizza_types.csv, and pizzas.csv, which I subsequently imported into MySQL Workbench.
**Files-- **orders.csv has columns :** order_id, date, time
order_details.csv has columns : order_details_id, order_id, pizza_id, quantity
pizza_types.csv has columns : pizza_type_id, name, category, ingredients
pizzas.csv has columns : pizza_id, pizza_type_id, size, price**

After applying data cleaning tasks such as checking for null values, duplicate rows and ensuring correct data types, I used INNER JOIN to combine all the tables to get the size of the dataset, resulting in a consolidated dataset 

### ✤ Analysis Questions
1.	How many unique types of pizzas are there on the menu?
2.	Which category (e.g., Chicken, Vegetarian) has the most number of pizza varieties?
3.	How many orders were placed? And how many pizzas were ordered in total?
4.	What is the average number of pizzas ordered in a single transaction?
5.	Which pizza has been ordered the most in terms of quantity?
6.	On which days of the week are the most orders placed?
7.	What is the distribution of quantity of pizza ordered by pizza size (small, medium, large)?
8.	How many orders contain more than one type of pizza?
9.	Can you determine the best and worst month in terms of order volume?

### ✤ Key Insights and Recommendations 
1.	The Pizza store's menu offers a diverse range of 32 unique types of pizzas, which is a good variety for customers to choose from. 
2.	The store received a total of 21,350 orders, resulting in the sale of 49,574 pizzas in 2015. 
3.	On average, there were 2 pizzas ordered per transaction. Encourage customers to order more items or upsell additional items like sides or drinks. This can be achieved through bundle deals, limited-time offers, or suggesting complementary items during the ordering process.
4.	The "big_meat_s" pizza was the most ordered, with a total quantity of 1,914. This pizza's popularity could be used to promote other similar items. 
5.	Friday is the busiest day of the week, with 3,538 orders. Offer Friday-specific promotions or discounts to capitalize on the busiest day of the week.
6.	Large pizzas are the most popular size, with 19,536 ordered, followed by medium (15,635) and small (14,403). Consider offering discounts or promotions for ordering larger sizes, enticing customers to upgrade.
7.	A significant portion (13,149 out of 21,350) of orders contain more than one type of pizza. Create combo deals for customers who order multiple types of pizzas. This can incentivize them to try different options.
8.	July had the highest order volume (1,935 orders), while October had the lowest (1,646 orders). Analyze seasonal factors that affect order volume. Plan marketing campaigns or seasonal specials to boost sales during slower months like October.

### ✤ Conclusion
Pizza orders and revenue maintains an upward trajectory from the beginning of the week Sunday and peaks on Friday before it starts dropping, this means most people prefer to eat pizza towards and during the weekend. Most people prefer to have the Pepperoni pizza for lunch on Fridays. It is advisable to make available tables and chairs to be able to accomodate the influx of the weekend, we can also explore the option of delivery services. The Ingrdients for Pepperoni pizza should be made readily available and in large quantities on or before Fridays. Since more orders are received on Fridays, a discount policy can be introduced every last Friday of the month where a customer gets 1 extra pizza when they buy 3 and above, this will encourage them to buy more.

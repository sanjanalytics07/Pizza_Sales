# Pizza Sales Analysis
The purpose of doing this project was to analyse the Pizza Sales of a Pizza Company/ outlet
so as to learn and improve its Sales Revenue and operations efficiency.
Multiple SQL queries have been executed using MySQL to answer business questions 
w.r.t the Pizza Sales

### Database Explanation
The database "pizzahut" has four different tables:

• The Orders table contains the date & time that all table orders were placed

• The Order Details table contains the different pizzas served with each order in the Orders table, and their quantities

• The Pizzas table contains the size and price for each distinct pizza in the Order Details table, as well as its broader pizza type

• The Pizza Types table contains details on the pizza types in the Pizzas table, including their name as it appears on the menu, the category it falls under, and its list of ingredients

### Findings

•	A total of 21350 orders were placed, which generated a total revenue of 817860.05

•	Highest priced pizza which the company has is "The Greek Pizza" costing 35.95

•	Customers prefer to have "L" sized pizzas, a total of 18256 "L" sized pizzas were ordered, making it the most common pizza size ordered
  Hence, outlet should always have "L" sized pizza ready to be ordered for all pizza types

•	The top most common Pizza types ordered are: "classic_dlx": 2453 orders placed, "bbq_ckn": 2432, "Hawaiian": 2422, "pepperoni": 2418, "thai_ckn": 2371

•	From each pizza category, total orders placed are: "Classic"- 14888, "Supreme"- 11987, "Veggie"- 11649, "Chicken"- 11050

•	When seen by hours, highest amount of pizza sales happens around 12 pm. Also, peak sales hours are between 12 to 1 pm and between 5 to 7 pm. 
  Least amount of pizzas are sold between 9 to 10 am. After 7 pm the pizza sales gradually decreases.

•	The outlet should have most number of employees available at the peak sales hours to avoid any possible bottle-neck

•	There are 4 different pizza categories available, "Chicken" with 6 pizza types offered, "Classic" with 8 pizza types offered, 
  "Supreme" and "Veggie" with 9 pizza types offered under each category

•	Average number of orders placed per day 138

•	Top 3 pizzas which gave the highest revenues are: "The Thai Chicken Pizza"- 43434.5, "The Barbeque Chicken Pizza" – 42768 and 
  "The California Chicken Pizza"- 41409.5

•	Percentage contribution of each pizza category: "Classic"- 26.91, "Supreme"- 25.46, "Chicken"- 23.96, "Veggie"- 23.68

### Insights Generated
•	During the peak business hours i.e. between 12 to 1 pm and between 5 to 7 pm when maximum number of orders are received,
  outlet should have most number of servers and chefs during these peak hours to run outlet operations effeciently by avoiding any possible bottle-neck
  
•	In the mornings between 9 to 11 am least numbers of orders are received, during these hours outlet can give certain offers like 10% discount on any pizza
  or buy-1-get-1 free pizza. Such offers would attract customer and increase the sales of total pizza of the day, 
  which would inturn increase average number of orders placed  per day
  
•	Classic Category Pizzas being most prefered amoung customers, contributing to a major percentage of total revenue, 
  their price can be increased to further increase the total revenue
  
•	Though in overall, Classic Category pizzas are more in demand, the top 3 pizzas which gave highest revenues belong to pizzas of Chicken Category

• Out of total 21350 orders placed while a total of 18526 orders where placed for "L" sized pizza (86.77% of total orders placed), 
  while only 28 orders were placed for "XXL" sized pizzas (0.13% of total orders placed). So, either the "XXL" size should be dropped off 
  or else it should be given in combo offers during the lunch hours between 1 to 3 pm to increase its sales

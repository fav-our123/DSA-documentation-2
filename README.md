# DSA-DOCUMENTATION 2
This is where I built my portfolio while taking the Data Analytics course with the Incubator hub in conjunction with DSA. Starting out as a self learner, this program helped to hone my skills, ranging from Ms-Excel to Power BI.
## PROJECT TOPIC 1: KULTRA MEGA STORES INVENTORY 
### PROJECT OVERVIEW
This Data Analysis Project seeks to provide key findings and insights for Kuktra Mega Stores between the year 2009 and 2012. Using mySQL, I analysed order and customer details to generate answers that guide customer engagement and order improvement, marketing strategies, and advice. This was done via SQL statements. 
#### DATA SOURCES
The dataset, as provided by DSA, contains information from Kuktra Mega Stores, including order details and customer preferences, with each row representing a unique product. The total records numbered 8,065 rows and 21 rows.
##### TOOL USED 
- MySQL for:
- Data manipulation
- Data analysis 

##### CASE SCENARIO 1. The code is attached below the case scenarios.
1. Which product category had the highest sales?
- Technology-5966969.82199999
2. What are the Top 3 and Bottom 3 regions in terms of sales?
TOP 3
- Nunavut- 105404.5935
- Northwest Territories- 759824.3275
- Yukon- 969683.7099999993
BOTTOM 3
- West- 3519628.4574999986
- Ontario- 2980039.5094999988
- Prairie- 2744113.4514999986
3. What were the total sales of appliances in Ontario?
- Null
4. Advise the management of KMS on what to do to increase the revenue from the bottom
10 customers
   - Promote and offer discounts plus bonuses on targeted sales.
   - Reach out through emails or other channels.
5. KMS incurred the most shipping cost using which shipping method?
- Express Air- 7368.1399999999685
##### Case Scenario II
6. Who are the most valuable customers, and what products or services do they typically
purchase?
- 
7. Which small business customer had the highest sales?
- Dennis Kane- 74298.54049999999
8. Which Corporate Customer placed the most number of orders in 2009 – 2012?
- 
11. Which consumer customer was the most profitable one?
- Emily Phan- 27220.69
12. Which customer returned items, and what segment do they belong to?
- No Return Column, so used the negative profits from the profit column
- 
13. If the delivery truck is the most economical but the slowest shipping method and
Express Air is the fastest but the most expensive one, do you think the company
appropriately spent shipping costs based on the Order Priority? Explain your answer
- You expect Express Air to appear more in Higher or Critical Priority Orders
- You expect Delivery Truck to appear more in Low or Medium priority
- If that's not the case, then the company may not be appropriately spending.

###### CODE


### Limitations

- This analysis was built on a single flat Excel file — which means there were boundaries I couldn’t cross, especially in deeper, joined queries.
- A few values were missing or unclear, and while I handled them carefully, I know some decisions may have influenced the final outcome.
- Dates weren’t always consistent, so I couldn't fully explore trends across time or seasonal insights.
- What you see is just a portion of the broader Amazon universe — so conclusions drawn here are more like glimpses, not full portraits.
- Because it was one table, complexity was simplified — for clarity’s sake, yes — but also due to structure.

### Recommendations

- This project would grow beautifully if expanded into multiple linked tables — customers, products, orders — allowing for richer relationships and queries.
- Data cleaning could be automated with Python (hello, pandas), so future work is smoother, faster, and more repeatable.
- A simple data dictionary could help others understand the “why” behind each column and choice made.
- Adding a visual layer — charts, dashboards, or even storytelling visuals — would make the insights easier to grasp at a glance.

### Next Steps

- Normalize the dataset and rebuild the queries with joins — that's one way to evolve the logic.
- Try visualizing customer patterns or product trends using Tableau, or Power BI.
- Explore segmentation, forecasting, or even predictive modeling.




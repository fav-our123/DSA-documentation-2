# DSA-DOCUMENTATION 2
This is where I built my portfolio while taking the Data Analytics course with the Incubator hub in conjunction with DSA. Starting out as a self learner, this program helped to hone my skills, ranging from Ms-Excel to Power BI.
## PROJECT TOPIC 1: KULTRA MEGA STORES INVENTORY 
### PROJECT OVERVIEW
This Data Analysis Project seeks to provide key findings ans insights to Kuktra Mega Stores. Using mySQL, I analysed order and customer details to generate answers that guides product improvement, marketing strategies, and customer engagement. Using the various parameters of the data, I answered several questions and plotted pivot tables. The cleaned datasets and pivot outputs were used to build an all emcompassing dasboard to aid visualization.
#### DATA SOURCES
The dataset, as provided by DSA, contains information scraped from Amazon product pages, including order details and customer preferences, with each row representing a unique product. The total records numbered 1,465 rows with 16 coulumns.
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
9. What is the distribution of product ratings (e.g., how many products are rated 3.0,
4.0, etc.)?
10. What is the total potential revenue (actual_price × rating_count) by category?
11. What is the number of unique products per price range bucket (e.g., <$200, $200-$500, >$500)
12. How does the rating relate to the level of discount?
13. How many products have fewer than 1,000 reviews?
14. Which categories have products with the highest discounts?
15. Identify the top 5 products in terms of rating and number of reviews combined.

[Click here to view the cleaned dataset and the pivot tables of the above](https://github.com/fav-our123/DSA-documentation/raw/refs/heads/main/Amazon%20case%20study%20(Autosaved)%20(Recovered).xlsx)

###### DASHBOARD
For easy visualization via charts and slicers:
![2025-07-03 (2)](https://github.com/user-attachments/assets/b3c4d50d-8760-4895-b7dd-bab997c831b9)

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




# DSA-DOCUMENTATION 2
This is where I built my portfolio while taking the Data Analytics course with the Incubator hub in conjunction with DSA. Starting out as a self learner, this program helped to hone my skills, ranging from Ms-Excel to Power BI.
## PROJECT TOPIC 1: KULTRA MEGA STORES INVENTORY 
### PROJECT OVERVIEW
This Data Analysis Project seeks to provide key findings ans insights to Kuktra Mega Stores. Using mySQL, I analysed product and customer review data to generate insights that guides product improvement, marketing strategies, and customer engagement. Using the various parameters of the data, I answered several questions and plotted pivot tables. The cleaned datasets and pivot outputs were used to build an all emcompassing dasboard to aid visualization.
#### DATA SOURCES
The dataset, as provided by DSA, contains information scraped from Amazon product pages, including order details and customer preferences, with each row representing a unique product. The total records numbered 1,465 rows with 16 coulumns.
##### TOOL USED 
- MS-EXCEL for:
- Data Cleaning and manipulation
- Data Visualization

##### ANALYSIS INSIGHTS
1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs the discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings (e.g., how many products are rated 3.0,
4.0, etc.)?
9. What is the total potential revenue (actual_price × rating_count) by category?
10. What is the number of unique products per price range bucket (e.g., <$200, $200-$500, >$500)
11. How does the rating relate to the level of discount?
12. How many products have fewer than 1,000 reviews?
13. Which categories have products with the highest discounts?
14. Identify the top 5 products in terms of rating and number of reviews combined.

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




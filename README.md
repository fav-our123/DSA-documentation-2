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
- 13	Emily Phan	89061.05	Polycom ViewStation™ ISDN Videoconferencing Unit
- 7	Jasper Cacioppo	45923.76	Polycom ViewStation™ ISDN Videoconferencing Unit
- 8	Craig Carreira	41343.21	Polycom ViewStation™ ISDN Videoconferencing Unit
- 47	Clytie Kelty	40780.52	Canon PC940 Copier
- 47	Peter Fuller	39053.75	Bretford Rectangular Conference Table Tops,Panasonic KX-P3626 Dot Matrix Printer
- 9	Dennis Kane	33367.85	Canon imageCLASS 2200 Advanced Copier
- 34	Steve Chapman	32916.73	Micro Innovations Micro Digital Wireless Keyboard and Mouse, Gray,Premium Transparent Presentation Covers by GBC,Riverside Palais Royal Lawyers Bookcase, Royale Cherry Finish
- 46	Seth Vernon	32636.83	Avery Poly Binder Pockets,Bush Westfield Collection Bookcases, Fully Assembled,Canon Image Class D660 Copier
- 48	Darren Budd	31423.070000000003	Bevis Steel Folding Chairs,Canon MP100DHII Printing Calculator,Global Stack Chair without Arms, Black,Telescoping Adjustable Floor Lamp
- 45	Lycoris Saunders	31214.029999999995	Bretford CR8500 Series Meeting Room Furniture,Eldon Expressions™ Desk Accessory, Wood Pencil Holder, Oak,Polycom VoiceStation 100,Xerox 1966
7. Which small business customer had the highest sales?
- Dennis Kane- 74298.54049999999
8. Which Corporate Customer placed the most number of orders in 2009 – 2012?
- Chuck Clark	13
9 . Which consumer customer was the most profitable one?
- Emily Phan- 27220.69
10 . Which customer returned items, and what segment do they belong to?
- No Return Column, so used the negative profits from the profit column for evaluation.
11. If the delivery truck is the most economical but the slowest shipping method and Express Air is the fastest but the most expensive one, do you think the company appropriately spent shipping costs based on the Order Priority? Explain your answer
- You expect Express Air to appear more in High or Critical priority orders.
- You expect Delivery Truck to appear more in Low or Medium priority.
- If that’s not the case, then the company may not be appropriately spending on

##### CODE
[CLICK HERE](https://github.com/fav-our123/DSA-documentation-2/blob/main/KMS%20SQL%20CASE%20STUDY)

##### Limitations
- Customers were not segmented by behavior, geography, or frequency. A deeper segmentation could have revealed more actionable insights.
- The project was executed using Excel and basic SQL. While sufficient for exploratory analysis, it does not leverage more advanced analytics or machine learning capabilities.
- Filters such as year range and customer segment were selected without external stakeholder input. This may introduce bias in the insights generated.

---
##### Next Steps
- Connect to APIs or live databases to keep the analysis current and continuously valuable.
- Translate this work into a dynamic dashboard using tools like Power BI, Tableau, or Google Looker Studio for better storytelling and usability.
- Introduce scripting (e.g., Python or R) to streamline data cleaning, transformation, and analysis.

---
##### Recommendations
For future iterations or those building on this project:
- Incorporate additional variables such as marketing spend, demographics, and sales channels for deeper insights.
- Implement forecasting models or classification algorithms to move beyond descriptive analysis.
- Collaborate with business units to validate assumptions and ensure the analysis aligns with real-world objectives.


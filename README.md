
# Car Price Prediction Analysis

In this project we will be focusing on Automotive industry. Getting insights from the data and analyse the Manufacturer point of view and Coustmer point of view.



## Case Study Description

**Project Description:**

This Project Focuses on automotive industry, how the Prices of Cars change based on fuel
efficiency, environmental sustainability, and technological innovation. We are going to conduct
analysis to know How can a car manufacturer optimize pricing and product development decisions
to maximize profitability while meeting consumer demand?


We will be analyzing the relationship between a car's features, market category, and pricing, and
identifying which features and categories are most popular among consumers and most profitable
for the manufacturer. By using data analysis techniques such as regression analysis and market
segmentation, the manufacturer could develop a pricing strategy that balances consumer demand
with profitability, and identify which product features to focus on in future product development
efforts. This could help the manufacturer improve its competitiveness in the market and increase
its profitability over time.

**Approach:**

The Data Source Used in the project is Car_data.csv, Which contains Columns like Make, Model,
Year, Engine Fuel Type, Engine HP, Engine Cylinders, Transmission Type, Driven_
Wheels, Number of Doors, Market Category , Vehicle Size, Vehicle Style, highway MPG, city
mpg, Popularity, MSRP.

Before Performing any analysis on the data we will be performing the Data Cleaning and
preprocessing like Outlier Analysis on the data.
The duplicates were first removed

Then We Handled the missing values there were very less empty cells so we directly removed them

Later we continued with the outlier analysis on the clean data, there are many numerical columns in the
data, we performed the outlier analysis only on 4 columns namely highway MPG, city mpg, Popularity,
MSRP. We cannot remove all the outlier data as we will be losing many rows so we only removed the
rows where all the four columns were outliers by using formula.
=AND(OR([@MSRP] <'Data Cleaning'!$B$15,[@MSRP]>'Data Cleaning'!$B$19), OR([@[city mpg]]<'Data
Cleaning'!$C$15,[@[city mpg]]>'Data Cleaning'!$C$19),OR([@[highway MPG]]<'Data
Cleaning'!$D$15,[@[highway MPG]]>'Data Cleaning'!$D$19),OR([@Popularity]<'Data
Cleaning'!$E$15,[@Popularity]>'Data Cleaning'!$E$19))
## Tech Stack
We have used
1. Microsoft Excel Professional Plus 2016.
2. Microsoft Word Professional Plus 2016.
3. Data Analysis Tool Pack from Excel.
4. Pivot Tables and Pivot Charts from Excel.


## Building the Dashboard

1. Creating Individual charts to answer the client’s questions is the first step. We have created multiple pivot tables and  necessary charts from the tables.

2. Now, we have created a new sheet in the same workbook and have given appropriate heading to the dashboard.

3. We have then copied all the created charts to the new sheet and named this sheet as Dashboard, keeping this as the first sheet made it to be available easily.

4. Now inserting the appropriate filters is important. After which we will connect all these filters and slicers to all pivot tables.

5. Now we will do all the necessary changes to make the dashboard more readable.

6. Keeping all the necessary legends and axis, other axis and legends will be removed.

7. After arranging everything is an order. We will check if the dashboard is interactive enough.

8. Finally, all the color coding will be done and our dashboard is ready.

<img src="/repository/assets/dashboard.jpg">


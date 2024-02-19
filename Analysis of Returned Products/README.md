# Returned Products Dashboard using Tableau

## Overview
* This is a mock project where I analyzed data for a company "Superstore". The project task what to help the company understand what is causing the high number of returned orders. Why do customers return their orders? How can the company reduce the volume of returned orders? I created an interactive dashboard for exectuives to use and a report that detailed my key findings and recommendations. 

### Questions answered from the analysis 

1. What is the return rate by the 3 product categories?
2. What is the return rate by month and state?
3. What is the correlation between number of sales and number of returns by product sub-categories?
4. what is the profit and return rate by product sub-category?
5. Which specific products have a high return rate and negative profit?
6. Which specific customers have the highest return rate?

### Key Findings/recommendations for Superstore
1. Geographically, the state with the highest return rate is Utah with a 57% return rate.
2. There are 7 specific customers with a return rate of 90% or more.
3. The sub-category with the highest return rate is ‘machines’ at 35%.
4. There are 10 specific products that have a high return rate of 75% or more, and negative total profit. Specifically, the Zebra Direct Thermal Printer has a return rate of 100% and the loss of total profit is -$4000.

### Interactivity of the dashboard
* Users can use the parameters on the left hand side to change the category, state, and order date (month) 
* On each visual, users can float their cursor above a certain data point. The tooltip will appear and give specific data for the specific data point. 

### Images
![Dashboard](https://github.com/saigeruleau/Data_Projects/assets/158613429/3f85f5f1-4ac9-4f3d-938e-1f0ff08c5ad9)

### Assumptions
* Returns can be measured in a few different ways. In this analysis, return rate as a percentage was mostly used. Return rate is usually the most appropriate measure because it is conditional to the number of sales. Return rate can be misleading when the sales count is low. For example, if an item was purchased twice, and returned once, the item would have a 50% return rate and this can skew data. Count of returns was also used, but only when it was analyzed against count of sales, thus making the absolute number appropriate.

[Click here to see live dashboard](https://public.tableau.com/app/profile/saige.ruleau/viz/SuperstoreMonitoringReturns/SuperstoreMonitoringReturns)
[Click here to see the presentation] (https://youtu.be/EsfI_eVJYNg)

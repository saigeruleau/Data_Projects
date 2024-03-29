# Restaurant Analysis Dashboard using Tableau

## Overview
* This is a mock project where I analyzed data for a multinational restaurant aggregator and food delivery company "Zomato". I created an interactive dashboard for exectuives to use and a report that detailed my key findings and recommendations. 

### Questions answered from the analysis 

1. What are the most popular restaurants by total revenue and number of sales?
2. What cities have the highest total revenue?
3. Is there a strong correlation between having a high average rating and generating more revenue? 
4. What are the most popular items and cuisines by revenue?
5. Is there a strong correlation between having a high average price and generating more revenue?
6. What is the best average price per food item for restaurants to make the highest revenue?

### Key Findings/recommendations for Zomato
1. 5 cities have a total revenue above $100,000: Tirupati, Bikaner, Sirsa, Sonipat, and Ranchi. Opening new restaurants in these 5 cities likely will generate more revenue rather than focusing on other cities that have not generated as much revenue.
2. Although having a high rating certainly does not hurt restaurant business, the data shows it is not an important characteristic for restaurant success. Thus, Zomato should not invest a lot of money or time on increasing restaurants’ average rating.
3. When acquiring new restaurants, Zomato should choose restaurants that have at least 1 of the top 20 food items, and are defined as 1 of the top 20 cuisines. Additionally, Zomato should inform current restaurants of the top 20 food items and recommend incorporating some of the food items into their menu.
4. Zomato should not acquire restaurants that have an average price per item above $51 since there are 0 restaurants in the top 100 that have an average price per item above $50.
5. Zomato should focus on acquiring restaurants that have an average price per item of $21-30, because this price bin category adds $531 in revenue per restaurant (2nd highest revenue per restaurant) and has generated more than $2M in total revenue.

### Interactivity of the dashboard
* Users can change the parameters (total revenue or number of sales) that defines if a restaurnat is popular
* Users can filter cities based upon what range of total revenue they wnat to see using the slide bar. Users can search for specific cities using the search bar
* Users can switch between most popular items or cuisines by the parameter 

### Images
![Dashboard](https://github.com/saigeruleau/Data_Projects/assets/158613429/ef1372d8-7f4d-4cc5-8efc-ff616df5a6c1)

### Assumptions
* Success of a restaurant, cuisine, or food item was defined by having a high total revenue or high number of sales.
* Data was compiled from 10/4/2017 to 6/26/2020.
* Null values were excluded from visualizations that needed those values to complete the analysis.
* When analyzing the cuisines of restaurants, some cuisines were grouped in order to combine similar cuisines. For example, ‘Indian’ cuisine includes ‘Indian, North Indian, South Indian’.

[Click here to see live dashboard](https://public.tableau.com/app/profile/saige.ruleau/viz/FinalProjectZomatoSaigeRuleau/ZomatoDashboard)

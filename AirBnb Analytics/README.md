# Airbnb Analysis Project using Google Sheets

## Overview
* This is a mock project where I analyzed Airbnb data for a client who wanted to invest in the vacation rental market in the Manhattan borough of New York City. The client is interested in investing in several properties but needs guidance on what types of properties they should be targeting. I analyzed data collected on current Airbnb listings to identify useful insights.

### Questions answered from the analysis 

1. Which neighborhoods are most attractive for vacation rentals?
2. Which size properties (how many bedrooms) are most popular for vacation rentals?
3. What's the average occupancy for each listing?
4. Which days of the week have the highest occupancy rates?
5. What is the estimated annual revenue for a property in 1 of the top 5 neighborhoods with the optimal size?

### Key Findings/Recommendations
* The most popular Manhattan AirBnb neighborhoods in order are Lower East Side, Hells Kitchen, Harlem, Midtown, Upper West Side, Chelsea, East Village, East Harlem, West Village, and Nolita. 
* The best property size ranges from 0 to 2 bedrooms. 1 bedroom is the most popular AirBnb property size in the top 10 Manhattan neighborhoods. I recommend to potential investors to choose a potential property that is 0-2 bedrooms. 
* Friday was found to have the highest average occupancy of all listings. 
* The annual estimated revenue for the top 5 neighborhoods and the corresponding most popular property size (based upon number of bedrooms) for each neighborhood was generated. The highest estimated annual revenue is $134,646.48 in the Hells Kitchen neighborhood with 2 bedrooms.
* For future analysis, investors could calculate the return on investment (ROI) by comparing the annual estimatted revenue and the average price of each property in the top 5 neighborhoods and the property's corresponding most popular size. 

### Project features 
* Executive summary: key findings from the analysis
* Table of contents: links to each sheet in the project
* Assumptions and change log: key assumptions made in the analysis and major changes made during the project
* Data dictionary: field names, data types, decription of field
* Raw data 
* Pivot tables: Top 10 most popular neighborhoods, best property size for the top 10 nieghborhoods, average occupancy of listings, average day of the week occupancy, estimated annual revenue for the top 5 neighborhoods with their respective best property size

### Images
<img width="516" alt="Image 1" src="https://github.com/saigeruleau/Data_Projects/assets/158613429/13e53910-7978-4806-ab1d-2c82baed3bb5">
<img width="869" alt="Image 2" src="https://github.com/saigeruleau/Data_Projects/assets/158613429/ec51a80e-a29a-4a8c-a8f3-371d85ad6ac8">
<img width="1072" alt="Image 3" src="https://github.com/saigeruleau/Data_Projects/assets/158613429/99dc57cf-b36c-4940-99f9-e8c219b605d8">
<img width="700" alt="Image 4" src="https://github.com/saigeruleau/Data_Projects/assets/158613429/528b9d6d-9491-4e99-a529-a8821abd27d2">

### Assumptions
* Listings with a minimum night stay of more than 7 nights were filtered out of the data. 		
* "Number_of_reviews_ltm" column (or reviews in the last 12 months) was used as the best estimate of how often a listing was rented.		
* Listings with less than 5 reviews in the last year were filtered out of the data because they are likely inactive listings or not applicable to the analysis because they are unpopular.
* For occupancy rate calculations, the dates from 2022-09-07 to 2022-10-06 were used. 		
* Only listings with >3 stars were included in the analysis.		
* Very inexpensive listings(<$100 per night) and very expensive listings (>$2000 per night) were not included in the analysis. 		

[Click here to see project](https://docs.google.com/spreadsheets/d/1Y_m3vb1Jl9VfJRB8rJD3gl-73kd3r_oFPLjjOoitZzM/edit?usp=sharing)

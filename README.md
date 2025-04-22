# Airbnb-Pricing-in-European-Cities
This project will provide a comprehensive analysis of Airbnb pricing dynamics in European cities by identifying key determinants of pricing The insights generated will benefit both hosts and travelers, offering actionable recommendations for optimizing listings and making informed booking decisions.  

# Project Overview
The "Airbnb Prices in European Cities" project aims to analyze and visualize pricing trends, geographical patterns, and guest satisfaction metrics across some of Europe's most popular cities. Using Tableau visualizations, this project explores the determinants of Airbnb prices, including room types, proximity to city centers, cleanliness ratings, and host attributes. By combining data from multiple cities and time periods (weekdays vs. weekends), I aim to provide actionable insights into pricing strategies for hosts and identify key factors influencing profitability as well as offer advice to travelers/tourists on accommodation pricing.

# Summary
This project utilizes a comprehensive dataset of Airbnb listings across ten European cities such as Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, London, Paris, Rome, and Vienna . The dataset includes attributes like room type, host characteristics, guest satisfaction ratings, distance from city centers, and geographical coordinates. Using Python for data preparation, combined with Tableau for visualization, I’ll create an interactive dashboard to explore pricing patterns and strategies. The final deliverable is a set of worksheets and a dashboard that highlight key insights, enabling stakeholders (hosts and travellers/tourists) to make informed decisions about Airbnb pricing strategies.

# Problem Statement
With the rapid growth of Airbnb listings across major European cities, both hosts and travelers face challenges in optimizing their decisions. Hosts seek to competitively price their listings and improve visibility and guest satisfaction, while travelers aim to find affordable, quality accommodations near points of interest.

# About the Data
The dataset was sourced from kaggle : https://www.kaggle.com/datasets/thedevastator/airbnb-prices-in-european-cities/data
Airbnb listings data for 10 European cities (Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, London, Paris, Rome, Vienna).
Data split into weekday and weekend files for each city. Data preparation involved combining all csv files into one and dropping entries with missing data.

Columns:
- price : The total price of the Airbnb listing. (Numeric)
- room_type : The type of room being offered (e.g. private, shared, etc.). (Categorical)
- is_shared_room : Whether the room is shared or not. (Boolean)
- is_private_room : Whether the room is private or not. (Boolean)
- capacity : The maximum number of people that can stay in the room. (Numeric)
- superhost  : Whether the host is a superhost or not. (Boolean)
- multi_listing :	Whether the listing is for multiple rooms or not. (Boolean)
- business_host : Whether the listing is for business purposes or not. (Boolean)
- cleanliness_rating : The cleanliness rating of the listing. (Numeric)
- guest_satisfaction_overall : The overall guest satisfaction rating of the listing. (Numeric)
- bedrooms : The number of bedrooms in the listing. (Numeric)
- city_center_distance : The distance from the city centre. (Numeric)
- metro_distance : The distance from the nearest metro station. (Numeric)
- longitude : The longitude of the listing. (Numeric)
- latitude : The latitude of the listing. (Numeric)
- city :  city name( Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, London, Paris, Rome, Vienna
- listing_period : weekday or weekend listing

# Analysis Worksheets and Dashboard
Link : [https://public.tableau.com/app/profile/moses.mugambi/viz/AnalysisofAirbnbPricesinEuropeanCities_17452248450510/HostStrategyDashboard?publish=yes](https://public.tableau.com/app/profile/moses.mugambi/viz/AnalysisofAirbnbPricesinEuropeanCities_17452248450510/HostStrategyDashboard?publish=yes)




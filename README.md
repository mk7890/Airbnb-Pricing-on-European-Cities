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
Link : https://public.tableau.com/authoring/AnalysisofAirbnbPricesinEuropeanCities_17452248450510/TravelersBookingAssistantDashboard#1

# Medium blog
Link : https://medium.com/@mugambimoses2/airbnb-insights-for-hosts-travelers-across-european-cities-c1f21b121e8a

# Website/App
Link1 : https://euro-airbnb-explorer.lovable.app/

Link2 : https://tempo-deployment-ed0e847f-7c75-4f19-ac37-275dd9c2b69-fjzfwaby0.vercel.app/

# Presentation
Canva Link: https://www.canva.com/design/DAGlTG7jE7Q/LSSGkEcX5vgD2KLvIXAtkg/edit?utm_content=DAGlTG7jE7Q&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

# Key Findings:
- Room Type Distribution : Majority of listings were composed of Entire home/apartment room type (Over 63%), Private room listings made up about 36% of all listings Shared room listings were less than 1% of total listings.
- Listings per Cityand by Room TypeTop 5 cities with most listings:London, Rome, Paris, Lisbon, Athens.Shared room type consistentlyremained the least popular categoryacross all cities.London, Rome and Lisbon are the topthree cities with the highestcombination of Entirehome/apartment and Private Room Types.
- Room Type Preferences : Entire home/apartment Room Type is the highest rated based onGuest Satisfaction ratings, with the Shared Room Type being theleast preferred.
- Most Affordable Cities for Entire home/apartment for the Weekend : Athens, Budapest, Rome, Vienna, and Lisbon are the mostaffordable cities for renting an Entire home/apartment for theweekend for less than 300 Euros per day.
- Influence of Distance from the City Center and the Nearest Metro Transport on Listing Price : Average listing price has negative correlation for the increase in both distancefrom the city center and nearest metro transport.
- Strategic Location Conviniences by City : For travelers/tourists wishing to stay close to a beach location, cities such asLisbon, Barcelona, Amsterdam, Rome and Athens are the most ideal to visit.
- Superhost Relation to Guest Satisfaction and Price : Guest satisfaction is higher under listingsoffered by a superhost.Superhosts don’t necessarily chargehigher than non-superhosts.
- Influence of Listing Cleanliness on Guest Satisfaction : Positive correaltion between cleanliness and guest satisfaction.
- Price Distribution by Room Type Across Cities : Entire home/apartment listings consistently rank highest in price across all cities.Amsterdam has the most expensive listings of all types.

## Host Recommendations
- Optimize Pricing Based on Location and Room Type : Listings closer to the city center and metro stations command higher prices—if your listing is further away, considerlowering the price or offering additional amenities to remain competitive.
- Aim for Superhost Status : Superhosts tend to have higher guest satisfaction . Focus on maintaining a high cleanliness rating, quick responses, and consistent 5-star reviews.
- Invest in Entire Homes for Higher Capacity Bookings : Larger-capacity and entire home/apt listings typically yield higher revenue per night. If feasible, consider converting space to accommodate more guests.
- Maintain Cleanliness & Ratings : Cleanliness and overall satisfaction are strong predictors of repeat bookings and positive reviews. Ensure thorough cleaning between stays and provide essentials (soap, fresh linens).
- Use Weekend vs Weekday Pricing Strategy : Analyze listing performance by day. If weekends have higher demand, adjust your rates accordingly using dynamic pricing tools.

## Traveler/Tourist Recommendations
- Look Beyond the City Center for Better Deals : Lis tings just a few kilometers from the city center or metro can be significantly cheaper while still being accessible.
- Choose Private or Entire Spaces for Comfort : While shared rooms are cheaper, private or entire apartments offer better comfort and security, especially for couples or families.
- Book with Superhosts for Reliable Stays : Superhosts consistently offer better hospitality, cleaner spaces, and higher-rated experiences, ideal for first-time or solo travelers.
- Travel Mid-Week for Lower Prices : Prices tend to dip on weekdays.
- Plan Ahead in for Cities with few listings : Cities like Amsterdam, Berlin, Barcelona, and Vienna often have high competition due to limited listings. Book early to get the best value.
- Focus on listings with high cleanliness scores and guest satisfaction for a better overall experience.

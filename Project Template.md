# General Data Analysis Capstone Project

# Project Title: Determinants of Airbnb Prices in European Cities

# Project Overview
This project aims to analyze and visualize pricing trends, geographical patterns, and guest satisfaction metrics across some of Europe's most popular cities. Using Tableau visualizations, this project explores the determinants of Airbnb prices, including room types, proximity to city centers, cleanliness ratings, and host attributes. By combining data from multiple cities and time periods (weekdays vs. weekends), I aim to provide actionable insights into pricing strategies for hosts and identify key factors influencing profitability as well as offer advice to travelers/tourists on accommodation pricing.

# Project Summary
This project utilizes a comprehensive dataset of Airbnb listings across ten European cities such as Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, London, Paris, Rome, and Vienna . The dataset includes attributes like room type, host characteristics, guest satisfaction ratings, distance from city centers, and geographical coordinates. Using Python for data preparation, combined with Tableau for visualization, I’ll create an interactive dashboard to explore pricing patterns and strategies. The final deliverable is a set of worksheets and a dashboard that highlight key insights, enabling stakeholders (hosts and travellers/tourists) to make informed decisions about Airbnb pricing strategies.

# Problem Statement (Objectives)
Airbnb hosts and travelers face challenges in understanding how various factors influence pricing across different European cities. Key questions include:

- What role do guest satisfaction metrics, room types, and host attributes play in determining prices?
- Are there significant differences in pricing between weekdays and weekends, and how can hosts optimize their pricing strategies accordingly?
- Are some cities more costly in terms of average listing price?
- How do location-based factors (e.g., distance from city center, proximity to metro stations) affect Airbnb prices?
- 
By addressing these questions, the project seeks to provide clarity on the determinants of Airbnb prices and offer actionable recommendations for hosts and travelers.

# Technical Details
## About the Data
Airbnb listings data for 10 European cities (Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, London, Paris, Rome, Vienna).
Data split into weekday and weekend files for each city.
https://www.kaggle.com/datasets/thedevastator/airbnb-prices-in-european-cities/data

## Tools and Technologies
Python : For data cleaning and merging.
Tableau : For creating interactive visualizations and dashboards.

## Analysis Techniques
- SQL for creating a database
- Tableau Visualizations: Bar charts, scatter plots, heatmaps, and symbol maps to explore relationships between various Dimensions and Measures.

# Structure
## Data Preparation
- Combine weekday and weekend CSV files into a single dataset.
- Clean missing values.
- Add derived features (e.g., city-specific indicators).
- Rename columns:


price : The total price of the Airbnb listing. (Numeric)
room_type : The type of room being offered (e.g. private, shared, etc.). (Categorical)
is_shared_room : Whether the room is shared or not. (Boolean)
is_private_room : Whether the room is private or not. (Boolean)
capacity : The maximum number of people that can stay in the room. (Numeric)
superhost  : Whether the host is a superhost or not. (Boolean)
multi_listing :	Whether the listing is for multiple rooms or not. (Boolean)
business_host : Whether the listing is for business purposes or not. (Boolean)
cleanliness_rating : The cleanliness rating of the listing. (Numeric)
guest_satisfaction_overall : The overall guest satisfaction rating of the listing. (Numeric)
bedrooms : The number of bedrooms in the listing. (Numeric)
city_center_distance : The distance from the city centre. (Numeric)
metro_distance : The distance from the nearest metro station. (Numeric)
longitude : The longitude of the listing. (Numeric)
latitude : The latitude of the listing. (Numeric)
city :  city name( Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, London, Paris, Rome, Vienna
listing_period : weekday or weekend listing


## Visualization
- Build individual worksheets in Tableau focusing on specific aspects (e.g., price distribution, geographical patterns).
- Combine worksheets into an interactive dashboard with filters and highlighting.
## Insights and Recommendations
- Summarize findings into clear insights.
- Provide practical recommendations for hosts and travelers.
# Project Timeline
Day 1: Data Preparation
- Extract and combine CSV files from the ZIP archive.
- Clean the data (handle missing values, remove unnecessary columns).
- Save the cleaned dataset for further analysis.
Day 2-4: Tableau Dashboard Creation
- Import the cleaned dataset into Tableau.
- Create individual worksheets (e.g., price distribution, geographical heatmap).
- Build an interactive dashboard with filters and storytelling elements.
Day 5-6: Article/Report writing and web app development


# Potential Challenges
- Dashboard Interactivity : Ensuring smooth interactivity and responsiveness in Tableau, especially with large datasets.
- Web app development.

# Future Improvements
- Expand Dataset : Include additional cities or regions to improve generalizability.
- Incorporate external data sources (tourism trends, seasonal demand).
- Include and explore time-series analysis to study temporal trends in pricing.





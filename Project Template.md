# General Data Analysis Capstone Project

# Project Title: Determinants of Airbnb Prices in European Cities

# Project Overview
The "Airbnb Prices in European Cities" project aims to analyze and visualize pricing trends, geographical patterns, and guest satisfaction metrics across some of Europe's most popular cities. Using spatial econometric methods and Tableau visualizations, this project explores the determinants of Airbnb prices, including room types, proximity to city centers, cleanliness ratings, and host attributes. By combining data from multiple cities and time periods (weekdays vs. weekends), we aim to provide actionable insights into pricing strategies for hosts and identify key factors influencing profitability.

# Project Summary
This project utilizes a comprehensive dataset of Airbnb listings across 10 European cities such as Paris, London, Berlin, and Barcelona. The dataset includes attributes like room type, host characteristics, guest satisfaction ratings, distance from city centers, and geographical coordinates. Using Python for data preparation and spatial analysis, combined with Tableau for visualization, we create an interactive dashboard to explore pricing trends and spatial patterns. The final deliverable is a set of worksheets and a dashboard that highlight key insights, enabling stakeholders to make informed decisions about Airbnb pricing strategies.

# Problem Statement
Airbnb hosts and travelers face challenges in understanding how various factors influence pricing across different European cities. Key questions include:
How do location-based factors (e.g., distance from city center, proximity to metro stations) affect Airbnb prices?
What role do guest satisfaction metrics, room types, and host attributes play in determining prices?
Are there significant differences in pricing between weekdays and weekends, and how can hosts optimize their pricing strategies accordingly?
By addressing these questions, the project seeks to provide clarity on the determinants of Airbnb prices and offer actionable recommendations for hosts and travelers.
# Technical Details
a. Data Sources
Airbnb listings data for 8 European cities (Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, London, Paris, Rome, Vienna).
Data split into weekday and weekend files for each city.
Attributes include realSum (price), room_type, host_is_superhost, cleanliness_rating, guest_satisfaction_overall, bedrooms, dist, metro_dist, lng, lat, etc.
b. Tools and Technologies
Python : For data cleaning and merging.
Tableau : For creating interactive visualizations and dashboards.
c. Analysis Techniques
Exploratory Data Analysis (EDA): To identify trends and outliers.
Visualizations: Bar charts, scatter plots, heatmaps, and dual-axis charts to explore relationships between variables.
# Structure
a. Data Preparation
Combine weekday and weekend CSV files into a single dataset.
Clean missing values.
Add derived features (e.g., city-specific indicators).


b. Visualization
Build individual worksheets in Tableau focusing on specific aspects (e.g., price distribution, geographical patterns).
Combine worksheets into an interactive dashboard with filters and highlighting.
c. Insights and Recommendations
Summarize findings into clear insights.
Provide practical recommendations for hosts and travelers.
# Project Timeline
Day 1: Data Preparation
Extract and combine CSV files from the ZIP archive.
Clean the data (handle missing values, remove unnecessary columns).
Save the cleaned dataset for further analysis.


Day 2: Tableau Dashboard Creation
Import the cleaned dataset into Tableau.
Create individual worksheets.
Day 3: Build an interactive dashboard with filters.

# Potential Challenges
Data Quality Issues :
Missing or inconsistent data may require imputation or removal.
Ambiguities in categorical variables (e.g., room types) need careful handling.
Dashboard Interactivity :
Ensuring smooth interactivity and responsiveness in Tableau, especially with large datasets.
# Future Improvements
Expand Dataset :
Include additional cities or regions to improve generalizability.
Incorporate external data sources (tourism trends, seasonal demand).
     2. Enhanced Visualizations :
Add animated maps to show changes in pricing over time.
Integrate user feedback mechanisms to refine insights
      3. Explore time-series analysis to study temporal trends in pricing.




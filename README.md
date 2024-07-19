# Air_BnB-NYC-Python-
Introduction
This project analyzes the Airbnb listings in New York City. The analysis covers various aspects including pricing, number of reviews, room types, and host activity. The goal is to uncover patterns and insights that can be useful for potential hosts, guests, and researchers.
# Dataset
The dataset used for this analysis is `AirBnB-nyc.csv`, which contains information on Airbnb listings in New York City. The dataset includes the following columns:
- `id`
- `name`
- `host_id`
- `host_name`
- `neighbourhood_group`
- `neighbourhood`
- `latitude`
- `longitude`
- `room_type`
- `price`
- `minimum_nights`
- `number_of_reviews`
- `last_review`
- `reviews_per_month`
- `calculated_host_listings_count`
- `availability_365`
Analysis
The analysis is performed using various Python libraries including pandas, numpy, matplotlib, and seaborn. Key steps in the analysis include:
Data Cleaning: Handling missing values and ensuring data integrity.
Descriptive Statistics: Calculating mean, median, min, and max prices for each neighborhood.
Visualization: Creating scatter plots, box plots, and pie charts to visualize the data.
Correlation Analysis: Exploring the relationship between price and number of reviews.
Results
Missing Values
Missing values were identified in the name, host_name, last_review, and reviews_per_month columns.
Price Analysis
The average price by neighborhood was calculated, and neighborhoods with the highest average prices were identified. Outliers in pricing were also detected.
Room Type Distribution
The distribution of room types was visualized using a pie chart:
Entire home/apt: 51.97%
Private room: 45.66%
Shared room: 2.37%
Host Activity
The top 10 hosts by the number of listings were identified, and the average number of listings per host was calculated.


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
  ![image](https://github.com/user-attachments/assets/4d6e6b73-32d7-49ed-aeb0-ca0d575bd979)
  ![image](https://github.com/user-attachments/assets/ec6cb35e-2d08-4a72-a355-0bed094730e7)



#Analysis
The analysis is performed using various Python libraries including pandas, numpy, matplotlib, and seaborn. Key steps in the analysis include:
-Data Cleaning: Handling missing values and ensuring data integrity.
![image](https://github.com/user-attachments/assets/22e6afa0-1c44-4f12-b101-97fa9b1616af)
![image](https://github.com/user-attachments/assets/df7899eb-c36c-4ab2-a1b5-2f55b8264d33)
![image](https://github.com/user-attachments/assets/0a7e637c-c642-4579-8bf5-240dde3593d8)
![image](https://github.com/user-attachments/assets/2398d0fe-0d02-4da0-9921-8c0b5f548a62)





-Descriptive Statistics: Calculating mean, median, min, and max prices for each neighborhood.
![image](https://github.com/user-attachments/assets/d3d82d60-2dc2-42c8-849c-a96f82f49b3b)
![image](https://github.com/user-attachments/assets/2ab3c7cb-af9b-45ab-8ba1-3f1f42b88be9)
![image](https://github.com/user-attachments/assets/ecba0269-6d88-4ff0-b32a-4b9dd393bc37)
![image](https://github.com/user-attachments/assets/b481cd62-48d9-46ce-98ff-1039d7951df2)




-Visualization: Creating scatter plots, box plots, and pie charts to visualize the data.
![image](https://github.com/user-attachments/assets/1681688d-a41a-4230-82ed-c4b938ac8196)
![image](https://github.com/user-attachments/assets/00ed9f65-ca5b-41a3-aea0-8a657025b486)
![image](https://github.com/user-attachments/assets/d909b498-b78d-440d-951a-9d9356ff9fda)
![image](https://github.com/user-attachments/assets/87af0e08-5f19-480e-bb7b-5beb6e6e1a1c)
![image](https://github.com/user-attachments/assets/f0945c7a-4d9f-40e0-aeec-4edb144c46a9)





-Correlation Analysis: Exploring the relationship between price and number of reviews.
Results
![image](https://github.com/user-attachments/assets/66354087-7e96-4348-9982-13139f6fc3f3)
![image](https://github.com/user-attachments/assets/8b5b018b-264d-4f4a-a8a1-941a7a56d46b)




#Missing Values
Missing values were identified in the name, host_name, last_review, and reviews_per_month columns.
Price Analysis
The average price by neighborhood was calculated, and neighborhoods with the highest average prices were identified. Outliers in pricing were also detected.
![image](https://github.com/user-attachments/assets/c0756d1d-cfe1-4f7f-b401-edf5a7d5f860)



#Room Type Distribution
The distribution of room types was visualized using a pie chart:
Entire home/apt: 51.97%
Private room: 45.66%
Shared room: 2.37%


#Host Activity
The top 10 hosts by the number of listings were identified, and the average number of listings per host was calculated.


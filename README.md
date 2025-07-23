# City-Rides-Platform-Dashboard-Excel-Project-
### Project Overview
This project analyzes a fictional ride-sharing dataset to extract insights on revenue, ride behavior and driver performance using Excel. It replicates a real-world data analytics task often given in business intelligence roles.
### Objective
To explore and visualize ride-sharing across different cities, drivers and fare, and to uncover insights that can help businesss stakeholders improve decision making regarding:
        •  Ride activity and revenue trends
	•  Effectiveness of promo codes
	•  Driver performance
	•  Driver performance by city
	•  Ride status performance (Active vs Inactive)
 ### 🧾 Dataset Summary
  Two datasets were used:
	•	Rides_Data: Contains ride-level data including fare, distance, duration, promo code, ride status, city, and rating.
	•	Drivers_Data: Contains information about each driver such as name, ID, and average rating.
 ### Data Claeaning & Transformation
 Performed in Excel using:
 • Vlookup: To get information from the Drivers_Data into the rides _data
 • Handling inconsistent data in the date column
 • Handling nulling values in Promo_code column (Replacing null values with no promo code)
 • Pivot table for summarizing metrics like: 
   Total Revenue
   Fare by Promo code, city, ride status
   Duration_min by city
   Total Rides
 • Calculated field for average fare, average duration e.t.c
 ### Analysis & Visualization
 This section present the key findings derived from the interactive dashboard.
 ### Dashboard preview
<img width="876" height="370" alt="dashboard png" src="https://github.com/user-attachments/assets/51a41867-6ca9-4240-86a5-9b97ff10a668" />

## Key Performance Indicator
• Total Rides: 1000 rides are completed
• Total Revenue: $44,560.47 was generated
• Total Rating: 4255.8
• Avg Rating: 4.3
• Total Duration_min: 49,664
• Avg Duration_min : 49.66

## Fare by city
 Los Angeles generated the highest Fare ($9,711.5) while Miami generated the lowest Fare(%8,305.4). There are High fare generated in Los Angeles and Chicago while the other cities generated  low fare.
<img width="788" height="413" alt="image" src="https://github.com/user-attachments/assets/a9f9c74f-a63a-43fd-b80e-e92e00ce488a" />

## Top 5 driver by Rating
Holly Li, Eric Greene, Amy Guzman, Aprill Rodriguez and Patrick Hall are the top 5 drivers with the highest Rating. Holly Li has the highest Rating among all the drivers (82.9) and Andrew Weaver has the lowest Rating (9.0) among all the drivers
<img width="507" height="274" alt="image" src="https://github.com/user-attachments/assets/971e4f52-d2a1-4d67-9db9-5852227de0e9" />

## Duration_min by City
Los Angeles has the highest duration_min (11444) while San Francisco has the lowest Duration_min (9344)
<img width="556" height="291" alt="image" src="https://github.com/user-attachments/assets/37a44095-76b4-43f7-946a-1b9afb6728d1" />

## Fare by Promo code
WELCOMES (11566.16) has the highest promo code given while SAVE20 has the lowest (10462.95)
<img width="553" height="295" alt="image" src="https://github.com/user-attachments/assets/1e18cb24-eb06-4b63-98be-c98be44093c8" />


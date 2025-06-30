# 🚗 Indriver Ride Analysis
<p align="center">
  <img src="Poster_final.png" width="1000px">
</p>

## 📊 Project Overview
This project analyzes monthly ride data from inDrive using an interactive Power BI dashboard. It tracks key metrics such as total trips, revenue, distance traveled, average fare, and trip time. The dashboard also breaks down performance by vehicle type, payment method, and popular pickup/drop-off locations. Daily trip patterns help identify peak demand days for better resource planning. User behavior insights support optimization of fleet allocation and pricing strategies. This analysis empowers inDrive to make data-driven decisions that improve efficiency and customer satisfaction. The insights serve as a foundation for scaling operations and enhancing the rider experience.

## Dataset Used

The analysis is performed on a single tables and columns with the following columns

- Trip Details Table

| Column Name       | Description                                                           |
| ----------------- | --------------------------------------------------------------------- |
| `Trip ID`         | Unique identifier for each ride/trip.                                 |
| `Pickup Time`     | Timestamp when the trip started.                                      |
| `Drop Off Time`   | Timestamp when the trip ended.                                        |
| `passenger_count` | Number of passengers for the trip.                                    |
| `trip_distance`   | Distance of the trip in miles.                                        |
| `PULocationID`    | Numeric ID representing the pickup location.                          |
| `DOLocationID`    | Numeric ID representing the drop-off location.                        |
| `fare_amount`     | Base fare charged for the trip in USD.                                |
| `Surge Fee`       | Additional fee applied during peak times or high demand.              |
| `Vehicle`         | Type of inDrive vehicle used (e.g., IndriverX, Indriver Black, etc.). |
| `Payment_type`    | Method of payment used (e.g., Payzapp, Cash, etc.).                   |

- Location Table

| Column Name  | Description                                                                |
| ------------ | -------------------------------------------------------------------------- |
| `LocationID` | Unique ID used to map trip pickup/drop-off locations.                      |
| `Location`   | Human-readable name of the area or neighborhood.                           |
| `City`       | City and region where the location belongs (e.g., Manhattan, Bronx, etc.). |

## 📊 Key Analysis Areas<br>
<p align="center">
  <img src="MonthlyAnalysis.PNG" width="1000px">
</p>

- **Overview Analysis**
1. Overall Trip Metrics Overview
   - Total Trips (**104K**): The business completed a total of 104,000 trips during the analyzed period, which is a high volume of transactions
   - Total Distance (**349K Miles**): This shows that the fleet has covered a significant distance, indicating that operations span large areas, possibly city-wide or in densely populated regions
   - Total Booking Value (**$2 Million**): This signifies that the business generated $2 million in revenue from these trips, which is a solid figure when considering the large number of trips taken
   - With **3 miles** as the average trip distance, it's likely the business operates in an urban area or city where short trips are more common, possibly catering to a daily commuter or urban resident demographic
   - The average trip time is **16 minutes**, confirming that these are relatively short, likely quick rides (e.g., from one part of a city to another), possibly for people on the go
   - The average booking value **($15)** seems low for each trip but when considering the large number of trips, it adds up to a significant total

2. Payment Method Breakdown (Payment Type)
   - **Payzapp** dominates as the preferred payment method **(67%)**, followed by Cash **(32%)**
   - The remaining Amazon Pay and Google Pay contribute much less, which could represent untapped potential for these digital payment methods
   - Since Payzapp leads, the business could explore loyalty programs or incentives that encourage further usage of digital payment methods to reduce cash handling
   - While cash transactions account for a significant portion **(32%)**, the business should aim to move customers toward digital payments. Promotions or small discounts for cashless payments could help in transitioning more customers
   - Amazon Pay and Google Pay are underused. Integrating promotional offers (e.g., discounts or cashback) for these methods could increase their usage
     
3. Vehicle Analysis
   - The **IndriverX** model leads with **38,744 trips** generating the maximum revenue, followed by **IndriverX Comfort (17,078 trips)**, and **Indriver Black (16,710 trips)**
   - The IndriverX model is the clear favorite, possibly due to price, comfort, or other vehicle-specific features. The business should consider expanding this fleet to meet demand
   - Even though IndriverX takes the most trips, other vehicles like Indriver Comfort and Indriver Black are also highly used, which shows a diverse customer preference

4. Location Analysis
   - **Penn Station/Madison Square West** stands out a sthe most frequent pickup location, followed by other locations like **Upper East Side North**
   - **Upper East Side North** is the most frequent drop-off location
   - The longest trip is from **Lower East Side** to **Crown Heights North**, covering **144.1 miles**, indicating the business is catering to longer-distance trips as well
   - **Penn Station** and **Madison Square West** are key pickup points, likely due to the concentration of customers in high-traffic areas. The business should ensure a high vehicle availability near these locations to capture demand
   - With **Upper East Side North** being the most frequent drop-off point, consider creating additional incentives or offers for passengers traveling to these areas to increase overall revenue

- **Time Analysis**


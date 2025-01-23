**Good Cabs - Ad -hoc analysis - Transportation Indstry**

**Tools - Python**

**Industry - Transporation**

**Function - Operations**

**The analysis is performed over 7 tables and around half a million records**

**Ad hoc  Business Requests**

**1.City Level  Fare and Trip Summary Report**

Required Fields:
city name 
total trips  
average fare per km 
Average fare per trip
The percentage contribution of each city’s trips to the overall trips.

This report will help in assessing trip volume, price efficiency and each city’s contribution to the overall trip count.


**2.Monthly City Level Trips Target Performance**

Generate a report that evaluates the target performance for trips monthly and city level. 
For each city and month, compare the total actual trips with the target trips and categorize the performance as follows:
If actual trips are greater than target trips, mark it as “Above Target”
If actual trips are below than target trips, mark it as “Below Target”

Additionally, calculate the difference between Actual and Target Trips to quantify the performance gap.

Required Fields:
City Name
Month_name
Actual Trips
Target Trips 
Performance Status
% difference 

**3.City Level Repeat Passenger Trip Frequency Report**

Generate a report that shows the percentage distribution of repeat passengers by the no. of trips they have taken in each city. 
Calculate the percentage of each repeat passengers who took 2 trips, 3 trips and so on, up to 10 trips

Each column should represent a trip count category, displaying the percentage of repeat passengers who fall into that category out of the total repeat passengers for that city 
This report will identify the cities with high repeat frequency, which can indicate strong customer loyalty or frequency usage patterns

Required Fields:
City name, 2- trip, 3- trip, 4- trip, 5- trip, 6- trip, 7- trip, 8- trip, 9- trip, 10- trip


**4.Identify Cities with Highest and Lowest Total New Passengers**

Generate a report that calculates the total new passengers for each city and ranks them based on this value.
Identify the top 3 cities with the highest number of new passengers as well the bottom 3 cities the lowest number of passengers, categorizing them as Top 3 or Bottom 3 accordingly 

Required Fields:
City name
total _new passengers 
City category top 3 or bottom 3 


**5.Identify Month with Highest revenue for each city** 
Generate a report that identifies the month with the highest revenue for each city. For each city, display month_name, the revenue amount for that city and
the percentage contribution of that month’s revenue to the city’s total revenue 

Required Fields:
City_name
Highest revenue month 
Revenue 
Percentage contribution 

**6.Repeat Passenger Rate Analysis**

Generate a report that calculates two metrics:

1.Monthly Repeat Passenger Rate : Calculate the  passenger rate for each city and month by comparing the number of repeat passengers to the total passengers.

2.City wide Repeat Passenger Rate: Calculate the Overall Passenger Rate for each city, considering all passengers across months 

Required Fields:
City name
Month 
Total passengers 
Repeat passengers
Monthly repeat passenger rate %
City repeat passenger rate %


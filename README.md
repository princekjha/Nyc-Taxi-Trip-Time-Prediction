# NYC taxi trip time prediction
<h1>About Project:-</h1>
The data is the travel information for the New York taxi. The problem is using
the regression method to predict the trip duration depending on the given variables.The variables contains the locations of pickup and drop-off presenting with latitude and longitude, pickup date/time, number of passenger etc.
<h2>ABSTRACT:</h2>
The objective of our model is to predict the accurate trip duration of a taxi from one of the pickup locations to another drop-off location. In today’s fast-paced world, where everyone is short of time and is always in a hurry, everyone wants to know the exact duration to reach his/her destination to carry ahead of their plans. So, for their serenity, we already have million dollar startups such as Uber and Ola where we can track our trip duration. As a result of this, we proposed a technique in which every cab service provider can give exact trip duration to their customers taking into consideration the factors such as traffic, time and day of pickup. 

<h3>The Nyc taxi time prediction Data is first extracted and then categorized to identify, analyze behavior data and patterns. Using this dataset in our Supervised ML-Regression project we found some relevant analysis which would help to predict the trip duration. </h3>



**Data set** - it contain Rows – 1048575, Features - 11 (Including Target) ,Target – Trip Duration Important 


### Independent Variables – 
*   **id** —  unique identifier 
*   **vendor_id** — a code indicating the provider associated with the trip record 
*   **pickup_datetime** — date and time when the meter was engaged 
*   **dropoff_datetime** — date and time when the meter was disengaged 
*   **passenger_count** — the number of passengers in the vehicle (driver entered value) 
*   **pickup_longitude** — the longitude where the meter was engaged 
*   **pickup_latitude** — the latitude where the meter was engaged 
*   **dropoff_longitude** — the longitude where the meter was disengaged 
*   **dropoff_latitude** — the latitude where the meter was disengaged 
*   **store_and_fwd_flag** — This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server — Y=store and forward; N=not a store and forward trip. 
### Target Variable – 
*  **trip_duration** — duration of the trip in seconds

<h3>The objective of this project is to predict the total ride duration of taxi trips in New York City.Discussion of Nyc taxi trip duration will involve various steps such as:</h3> 


1.	Loading the data into data frame 
2.	Cleaning the data 
3.	Extracting statistics from the dataset 
4.	Exploratory analysis and visualizations
5.	Train Test Split 
6.	Linear Regression 
7.	Decision tree
8.	Random forest 
9.	decision tree with GridsearchCV


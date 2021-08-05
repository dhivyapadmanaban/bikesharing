# Bike Sharing Analysis

## Overview of the Analysis

The purpose of this project is to analyze the New York City Bike Program, the largest bike sharing program in the United States and build a business proposal to convice investors of the bike-sharing program in Des Moines!

Here is the detailed analysis of NYC Bike ride program - [New York City bike Dashboard](https://public.tableau.com/app/profile/dhivya5143/viz/NYCBikeChallenge_16274960011200/NYCCitibikeanalysis?publish=yes)

## Data Sources

August month CSV file (Busiest month) is collected from [Citi Bike Data webpage](https://s3.amazonaws.com/tripdata/index.html).

## Analysis Results

There are various visualizations created in Tableau to support the analysis. Few key visualizations which supports the new business proposal are explained below.

### Subscribers vs Customer - NYC CitiBike

As per below pie chart, NYC CitiBike has around 80% subscribers than the customers. Subscribers are local people who use bike for regular commute hence this model is sustainalbe in Des Monies with local subscribers.

![image](https://user-images.githubusercontent.com/83181834/128300938-a7990a82-fcc3-43ac-af53-ef08311f1cea.png)

### Gender Breakdown of Bike users

Below pie chart shows majority of the users are Male than Female!

![image](https://user-images.githubusercontent.com/83181834/128301123-7bebee34-8939-4905-b957-a11a9017971e.png)

### Trips by Weekday

Heatmap captures the trip time by bike users on weekday. As per below heatmap peak hours are from 8 AM - 10 AM and 5 PM - 7 PM and Thursday has more bike traffic compared to other weekdays!

![image](https://user-images.githubusercontent.com/83181834/128301349-08f2a362-e834-4f09-921e-b74ab9e4b4a7.png)

### Trips by Gender

This heatmap captures the bike trip between Male and Female riders. While the map is similar to previous map on peak hours, its much darker for Male because of more number of riders. Also bike riding is little busy on weekends from 10 AM - 5 PM !

![image](https://user-images.githubusercontent.com/83181834/128301573-76826815-b8d7-493b-b43e-18b12b6a5e17.png)

### User trip - Gender

This heatmap has all the key metrics from dataset like user type, gender and bike traffic. As expected bike traffic is heavier for subscriber compared to customer hence the map is darker. 

![image](https://user-images.githubusercontent.com/83181834/128301773-9518c3a3-eb98-47fe-bb9e-927122897e79.png)


### Checkout time for Users / Gender

This line chart shows detailed information of number of bikes checked out by users per hour and minute duration. Following chart shows similar data by Gender category.

![image](https://user-images.githubusercontent.com/83181834/128302204-d7d298bd-4666-4847-9b60-50c526c978ea.png)

![image](https://user-images.githubusercontent.com/83181834/128302348-e77e9480-631a-46b0-9fd5-6d9456952837.png)

### Bike Utilization

Here we are going to find the most used / popular bikes by measuring their trip duration! Packed bubbles is a great way of showing huge data. Bigger darker bubbles are most used bikes.

![image](https://user-images.githubusercontent.com/83181834/128302540-30b72c3b-2453-46ec-9c92-34467791983b.png)

### Bike Repair

We need to identify the bikes which are used on many trips to help with the better utilization and maintainance. This treemaps easily tell us the bike ids with most number of trip and we can user the downtime window (4 AM - 6 AM) for bike maintainance. 

![image](https://user-images.githubusercontent.com/83181834/128302865-d7a1afb2-2de5-4cd3-b921-54b447aeae09.png)

## Summary

As per these analyzed visualizations, we can start similar business in Des Moines on Bike sharing program ! Since majority of the users are subscribers, we can launch the program for Des Moines locals. Temporary customers like tourist , visitors will user bikes for shorter commute within Des Moines! 

In addition to these visualizations, below charts will add more depth to the analysis. 

#### Membership Breakdown By Day

This stacked bar chart quickly shows us the user typers of this bike sharing on everyday basis. As expected subscribers take most of the trips everyday!

![image](https://user-images.githubusercontent.com/83181834/128304690-5fec08f1-1901-4cf3-8953-ecbf58d2a831.png)

#### Riders by Age

This packed bubbles charts shows us the riders age group ! This is a key detail in knowing more about the customer base before launching the bike sharing program.

![image](https://user-images.githubusercontent.com/83181834/128304982-4ba42700-9b78-4d54-9b03-49c5bb2a76a5.png)

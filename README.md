# NYC CitiBike Analysis
## Purpose
The purpose of this report is to analyze NYC bike share data in August. The analysis uses Tablueau to visualize time, gender, location, and count of rides data. The full Tableau story can be found at the link below.

## Overview of Project
Des Moines requested data for a business proposal to determine if it is a good investment. August 2019 Citibike data from NYC was used to create graphs and a storyboard to display the information gathered. It will display different graphs that shows peak ridership and length of trips and other elements of the data which will determine if Citibike would be a good investment.

## Coding and Data Resources
### Coding Resources
Python Data, Jupyter Notebook
### Data Resources
Citi Bike System Data Page: 201908-citibike-tripdata.csv

## Data Cleaning
The 201908-citibike-tridata.csv file was downloaded and opened in Jupyter Notebook. After a review of the data it was determined that the tripduration column needed to be modified to fit our purposes. The tripduration field needed to transformed from an integer to datetime64[ns]. This was achieved by using Python code via Jupyter Notebook. Below will show the transformation.

Fig #1
Data file prior to transformation

Fig#2
Data file post transformation

## Analysis Results
1.	Bike Ride Length
![Bike_Ride_Length](https://user-images.githubusercontent.com/113568268/220212039-287f1d43-45f6-44d8-afe9-dea53062b4ad.png)


2.	Trips By Weekday

![Trips_by_weekday](https://user-images.githubusercontent.com/113568268/220212287-e8379d36-6f9a-459c-8a88-028abf16d98a.png)

3.	Peak Bike Check Out
![Peak_Bike_Checkouts](https://user-images.githubusercontent.com/113568268/220212337-80e798ff-cbd1-45f0-89c1-1cdc56790535.png)


4.	Check Out times for Users
![checkout_times_for_users](https://user-images.githubusercontent.com/113568268/220212360-9cda5d74-6d58-48de-8e7e-55ae7517bf42.png)


5.	Check Out Times By Gender
![Checkout_times_by_gender](https://user-images.githubusercontent.com/113568268/220212385-d76c5fbc-c28f-4fb3-a2b2-38bd0a18c666.png)


6.	Weekday Trips Per Hour

![weekday_trips_per_hour](https://user-images.githubusercontent.com/113568268/220212404-88e0f7d9-757a-47c1-b650-2d47e39ed497.png)

7.	Trips By Gender (Weekday Per Hour)
![trips_by_gender_weekday_per_hour](https://user-images.githubusercontent.com/113568268/220212456-d8139a0f-797c-4eae-9ff2-becfb5a87c67.png)


8.	User Trips By Gender Weekday
![users_trips_by_gender_by_weekday](https://user-images.githubusercontent.com/113568268/220212496-7f35b63f-dfaa-41e1-921d-e303bcc5337c.png)


## Summary
Overall Males are the most frequent users of Citibike. In general, for both genders the peak hours are around 6am-9am and 4pm-7pm. This corresponds with the beginning of the workday and the end of the workday. For this program to work in Des Moines the male population should have targeted marketing, with an emphasis on the convenience of getting to and from work. What was also discovered that subscribers contributed the most revenue. In addition, marketing to the single-use rider with an emphasis on weekend and outdoor activities would be beneficial. With this two-pronged approach this would reach the most potential riders and increase the chances of this being a successful business venture.


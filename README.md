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

##Analysis Results
1.	Bike Ride Length

2.	Trips By Weekday
3.	Peak Bike Check Outs
4.	Check Out times for Users
5.	Check Out Times By Gender
6.	Weekday Trips Per Hour
7.	Trips By Gender (Weekday Per Hour)
8.	User Trips By Gender Weekday
## Summary
Overall Males are the most frequent users of Citibike. In general, for both genders the peak hours are around 6am-9am and 4pm-7pm. This corresponds with the beginning of the workday and the end of the workday. For this program to work in Des Moines the male population should have targeted marketing, with an emphasis on the convenience of getting to and from work. What was also discovered that subscribers contributed the most revenue. In addition, marketing to the single-use rider with an emphasis on weekend and outdoor activities would be beneficial. With this two-pronged approach this would reach the most potential riders and increase the chances of this being a successful business venture.


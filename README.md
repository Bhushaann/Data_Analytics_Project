# Data_Analytics_Project
## Gist
My Capstone Project for Google Data Analytics where I had a few Problem Statements about a company, Was provided with a raw public dataset. The data was available in a monthly format, I downloaded the data in Excel format ( 10 Excel files ) Later stacked them up with power query which resulted in aporox 5.8 Million rows of data, Cleaned the data after which it resulted in around 4.4 million rows of data, Transformed/Prepared it in various ways, Later Visualised it with the help of Microsoft Power Bi making interactive Dashboards & Reports.
## About the Company
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime. They offer three types of passes for their Customers: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members. Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno (Stakeholder) believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs. Moreno has set a clear goal.
## Problem Statements
* Design marketing strategies aimed at converting casual riders into annual members.
* How annual members and casual riders differ, why casual riders would buy a membership
* How digital media could affect their marketing tactics.
* Team is interested in analyzing the Cyclistic historical bike trip data to identify trends
## About the Data Source
The link to the data source was attached with the Problem statement. The data was observed as follows. 
![](pictures/Data%20Source%20pic.png)

## About the Data Set
The data was contained in .zip format as per their month after downloading. 
The data was further unzipped, Later transferred to excel. It was stacked up on Microsoft Power Query editor. It had a lot of empty cells in a lot of columns, Data was jumbled it, not in the right format.
![](pictures/Raw%20data.png)

The data approximalety had 5.8 million rows and 14 columns. 

![](pictures/Raw%20count.png)

## How I cleaned & Manipulated it
* Raw data had a cell in Date/Time Format containing both from which I made the start Date, end date & start Time, end time Separate
* From the End time & Start time I calculated the trip duration and handle the negative outputs by Square & Square root
* From Date column, I extracted the Quarter, Day name, Months name, Weekday/Weekend
* From time I extracted the Hours of the day in 24 hour format.
 Here are the applied steps to the entire Data set.
  ![](pictures/C%26M.png)
  ![](pictures/C%26M2.png)
  ![](pictures/C%26M3.png)

### The cleaned data had over 4.4 million Rows and 18 Columns
 ![](pictures/Clean%20data%20count.png)

## Visualisation Phase
The Data was finally cleaned, Prepared and was ready to Visualise.

### The first main dashboard contained information with option to Segregate between Members & Casual riders :
* Total count of Casual or Member riders or Total
* Max number of riders by total ridership in the span of 1 year
* Average duration of rides as per selected subscription type or total
* Max Trip duration as per selected subcription type or total
![](pictures/Main%20Dashboard.png)

### Second page inclucions :
*Comparision of ridership as per selected Subscription type by 7 Days_of_the_week
*Comparision of ridership as per selected Subscription type by Different types of bikes available
![](pictures/Pg%202.png)

### Third Page inclusion :
* Start, End latitude & Start, end longitude co-ordinates were provided in the data set
* Geographical mapping of the Start Longitude & Latitude was done as follows :
![](pictures/Pg%203.png)

### Fourth Page inclusion :
*Comparison of Selected Subscription Type by Hour of the Day
![](pictures/Pg%204.png)

### Fifth Page inclusion :
*Comparison of Selected Subscription Type by Weekend/Weekday
![](pictures/Pg%205.png)

## Conclusion

### Usage Segregation by Subscription Type
* 4.49M bike rides registered Total, 1.75M were Casual rides, 2.75M Member riders
* 15.92 mins average trip duration for Casual riders, 11.05mins Avg trip duration for Member riders

### Average ride time
* 59 mins was the max trip duration for both the ride types
  
### Usage Segregation as per months by Subscription Type
* For Casual riders top 5 months were namely July, June, August, September, May, after which the rides dipped 48% from july (max)
* For Member riders Top 5 months are May, June, July, August, September after that the it barely drops 25%
* Least of both Subscription type rode in January, December, February (winters)

* ### Usage Segregation as per Days_of_week by Subscription Type
* Saturdays had the highest number of total rides approx 690k, Monday had the lowest number of rides approx 570k
* Majority Casual riders 350k rode on Saturday, Lowest 190k rode on monday
* Majority Member riders 460k rode on Wednesday, lowest 300k rode on Sunday
  
### Usage Segregation as per bike_type by Subscription Type
* Majority 259k used the classic bike, lowest 150k used the docked bike
* Majority Mmeber riders users 173k rode the classic bike, there were no docked bike users
* Casual riders 860k used the classic bike, lowest Casual riders 150k rode the docked bike
  
### Usage Segregation as per Geological mapping (Latitude&Longitude) by Subscription Type
* Casual riders used to inside suburbsof Chicago more than members, Member riders were highly concentrated on the chicago bay area
  
### Usage Segregation as per Time_of_day by Subscription Type
* Majority 171k Casual riders used the bike at 5:00pm, Lowest Casual bike rides 4k at 4:00am
* Majority 298k Member riders used the bike at 5:00pm, Lowest Member bike rides 4k at 4:00am
  
### Usage Segregation as per Weekend_Weekday by Subscription Type
* Weekdays had the most number of rides 3.2miliion, Weekends had the least with 1.2 million
* Casual had 1.1million rides on Weekdays and 640k on Weekends, 2.1 million on Weekdays and 647k on Weekends 









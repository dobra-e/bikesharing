# The CitiBike Story

## Overview
CitiBike is a bikesharing program powered by Lyft that operates in the New York City area including Manhattan, Brooklyn, Queenx, the Bronx, Jersey City, and Hoboken. It is the largest bike sharing program in the United States. After seeing the success of CitiBike in NYC, there is a a desire to bring the program to Des Moines, Iowa. The purpose of this analysis is to provide potentional investors with data about usage to inform their investment decision.

## Analysis
CitiBike data was first transformed using Python. In particular, the 'tripduration' column datatype was changed from integer to datetime. Tableau was then used to visualize trip data from CitiBike for the month of August (the month with peak usage). 

## Results
Explore the [CitiBike Story on Tableau Public](https://public.tableau.com/app/profile/emily4932/viz/CitiBike_16777247951230/TheCitiBikeStory?publish=yes).

#### Visualizations used in the story are below with a brief description of the resulting conclusions. 

##### User Types
![User Types](/visualizations/customers.png)

* Users of CitiBike are classified into one of two groups: customers and subscribers. The majority (about 81%) of users are subscribers.

##### Peak Usage Times in August
![Peak Usage Times in August](/visualizations/AugustPeakHours.png)

* CitiBike's peak hours of usage are during the morning and evening commutes, 8am and 5-6pm, respectively. 

##### User Checkout Times
![User Checkout Times](/visualizations/Checkout_Users.png)

* Bikes are typically checked out for 5 minutes. Most trips are less than 20 minutes. 

##### User Checkout Times by Gender
![User Checkout Times by Gender](/visualizations/Checkout_Gender.png)

* Males checkout bikes more than other genders and checkout bikes for longer periods of time.

##### Usage Time and Day
![Usage Time and Day](/visualizations/TripsByDayHour.png)

* Between Monday and Friday, the fewest trips are taken on Wednesday. Thursday is the busiest weekday, particularly during the morning and evening commute hours.

##### Usage Time and Day by Gender
![Usage Time and Day by Gender](/visualizations/TripsByDayHourGender.png)

* Trends found in the previous visualization hold true when the data is grouped by gender. Across genders, the fewest trips are taken on Wednesday and the most are taken on Thursday. 

##### Usage by Day, Gender, and User Type
![Usage Time and day by User Type](/visualizations/TripsbyDayGenderUser.png)

* Across all days of the week, most trips are taken by male subscribers, with Thursday's having the highest trip count.

## Summary
Most CitiBike trips occur around 8a and 5-6pm indicating CitiBike is a popular method of transportation for commuters. Most users are program subscribers and the majority of trips are taken by males. Trips are typically 5-6 minutes long which indicates that CitiBike is used to get from place to place quickly opposed to strolling through the city or as a means of longer duration exercise.

#### Additional Visualizations
To learn more about the CitiBike program, an analysis of trip count by gender and age as well as trip duration by gender and age could provide useful information for marketing the program to a target population. Also, mapping the most popular CitiBike stations and comparing the locations to businesses in the area could provide insight into where CitiBike stations should be built in Des Moines to ensure success.

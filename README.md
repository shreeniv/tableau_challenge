# tableau_challenge

Jersey City Citibike Data for all months of 2020 and only the Summer months (June, July, August) of 2019 has been used. 

The following visualizations were created:
1. Popular Stations with plots of populare start and end station:
	a. Map based on Start Station Longitude and Start Station Latitude.  Color shows number of rides by location.  Size shows count of rides.
	Observation: Groove St Path seems to be most popular Start station with rides upto 37736 ending there followed by Newport Parkway and Hamilton Park stations

	b. Map based on End Station Longitude and End Station Latitude.  Color shows number of rides by location.  Size shows count of rides.
	Observation: Groove St Path seems to be most popular End station with rides upto 44371 ending there. Popular start and end stations almost remain the same with 	varying counts.

2. Summer Rides plot with Number of Bike Rides plotted against time (in hrs) between Summer months of 2019 & 2020
Observation: Due to covid, there certainly is a decrease in the number of rides. However August is still the most popular month and 6pm is the most popular time of the day in both 2020 and 2019 among riders.

3. Summer Trip Durations by Gender plots the sum of Tripduration (in secs) for each Month broken down by Gender and Starttime (24hrs).  Color shows details about Gender. The view is filtered on Gender and Starttime (24hrs) Month. The Gender filter keeps Male and Female. The Starttime (24hrs) Month filter keeps June, July and August
Observation: The number of riders have reduced greatly between the 2 years - for obvious reasons like Covid. However overall in both the summers Males have taken more trips than females during the summer months 

4. Number of Rides count by Age: total number of rides plotted against each age group
5. Trip Duration by Age: Average of Trip duratiion plotted for each Age group. Color shows details about Age (groups). The data is filtered on Age, which ranges from 17 to 75
Observation: Strangely, 17, 21 and 52 year olds almost have rides averaging to an hour - which proves 'Age is just a number!' Overall, 'under 20' age-group have more trip durations - may be because overall rides were less and hence trip duration averages peaked. Citibike is popular among age-group between 21 to 35 as they account for the maximum riders and hence overall high avg in trip duration. 

6. Gender vs Rides: Color shows details about Gender.  Size shows count of Bikeid.  The marks are labeled by Gender and count of Bikeid. The view is filtered on Gender, which keeps Male and Female
Observation: Given the total of 405537 rides, there are more male riders 290499, when compared to female 115038.

7. Average of Trip Duration (in mins) for each Age (groups).  Color shows details about Gender. The data is filtered on Age (in yrs), which ranges from 17 to 70. The view is filtered on Gender, which keeps Male and Female.
Observation: Since the number of riders within the 'under 20' age group is less when compared to the overall riders, the average trip duration seems to be highest in that age group; age group above 65 seem to have the lowest average trip duration. 

8. UserType vs Gender: Gender, Usertype and count of Bikeid.  Color shows count of Bikeid.  Size shows count of Bikeid.  The marks are labeled by Gender, Usertype and count of Bikeid. The view is filtered on Gender, which keeps Male and Female
Observation: Male subscribers top the list with more than 250k rides.

OPPORTUNITIES
1. Citibike can run promotions to motivate and increase the number of female riders overall
2. Campaigns can be run to motivate the use of citibike rentals for school and college students - this might help with increasing the usage under 20 age group
3. Promotions and discounts could be announced for frequent customers and also based on the average trip durations - this might help in increasing the overall customer to subscriber ratios
4. Since the top 3 start stations are pretty close to one another, there is an opportunity to add another station to regulate usage during peak hours. There are a number of start and end stations with very few rides - there can be incentive programs run to promote the usuage of stations like Christ Hospital, Montgomery St, etc.
5. Explicitely sharing the multiple actions taken by Citibike in order to support riders and making people from neighborhood communities aware of these measures would encourage more riders to use citibike during situations like pandemic. Also can run promotions with people with previous year's citibike - this might help with returning customers and also considering current economic situations. This might help citibike with sustaining the rides during pandemic times. 

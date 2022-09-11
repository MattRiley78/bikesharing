# NYC CitiBike User Analysis
## Project Overview
To demonstrate the feasibility of implementing a pay-per-ride bike share program, this analysis will show how this type of service has been successfully implemented in a large urban market and has been integrated into daily routines for many commuters.  All usage data from the CitiBike program in New York City has been rendered for this analysis.

## Methods
All NYC CitiBike rider usage data from August 2019 has been included in a CSV file.  Trip Durations were listed in number of seconds.  In order to convert Trip Durations to a Datetime format, the data type was first imported in Jupyter Notebook using Python and Pandas, converted to Datetime format, then exported into an updated CSV file.


## Results
Full Tableau Story can be viewed here:  
[Link to Story](https://public.tableau.com/app/profile/matt.riley/viz/NYCCitiBikeChallenge_16628530084930/TripsGenderWkDay)
### **Trip Durations**
Most trips in an urban downtown market are from residents who live near their places of work, and where other modes of transportation are not practical or feasible for a multitude of reasons.  The peak length of usage is about 5 minutes, and then drops off sharply.  There is not much ridership after the first hour.

### **Trip Durations by Gender**
The vast majority of riders are males.  There are fewer female riders.  The peak length of usage is about the same: around 5 minutes.  Other/unknown gender types tend to ride longer.  All ridership drops to near zero after the first hour.

### **Peak Usage by Hour**
As can be seen, ridership peaks during morning and after work rush hours.  This is evidence that the majority of riders are using for the daily commutes.

### **Trips by Weekday by Hour**
Breaking down by day, the work week (Mon - Fri) shows peak ridership during morning and afternoon commute hours.  There is moderate weekend usage through the daylight hours with an intense peak usage.

### **Trips by Weekday by Hour by Gender**
Breaking down the previous map by Gender.  Declared male and female riders have a similar imprint during the weekday rush hours and weekend times.  Unknown/other genders tend to ride more on the weekends.  This may also contribute to their longer trip durations as seen on a previous chart.

### **Customer Type and Daily Usage**
Chart shows that CitiBike has been successfully integrated into the daily commute routines of users.  A vast majority of riders use the subscription service.

### **Customer Type and Daily Usage by Gender**
Male/female riders make up most of the subscribers.  Relatively speaking, there are very few unknown/other genders that are using the subscription service and many more that are single-use customers.  This may show potential challenges in future marketing strategies, which could focus on increasing subscribers from Unknown/Other genders who are also not using the service for daily commutes.

## Summary
Des Moines has a quickly growing urban area with more people moving to downtown to be close to their places of business.  Using the NYC CitiBike as a model, Des Moines can implement a bike-sharing program for commuters.  As shopping areas downtown continue to grow, this would also be a great addition for weekend riders.  It can easily be marketed to males, who are more likely to use the program.  Then, the marketing focus can shift to attracting more female riders, as well as other gender riders.

Further analysis of this dataset could include Customer Types by Age.  An additional project can determine average trip length by comparing starting latitudes/longitudes with ending latitudes/longitudes by Bike ID.

If a similar dataset is compiled for our own BikeShare service, then we will also be able to show specific bikes that have been used the most and will most likely be in need of repairs.  This will help with maintenance budgets.


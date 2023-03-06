
# Bikesharing Overview
The aim of this report is to understand the needs of a bikesharing business in Des Moines, Iowa. This report draws from New York City citibike trip data and [monthly operating report](https://d21xlh2maitm24.cloudfront.net/nyc/August-2019-Citi-Bike-Monthly-Report.pdf?mtime=20191217092445) for August 2019. 

## Results
According to citibike's monthly operating report, total revenue for the month alone was 6.5 million, and is made up from user fees and sponsorship. By reviewing the data for this month we can aim to understand the factors that have made citibike successful in NYC, and how the service can be improved upon in a new city. All the visualizations below, and more, can be found on this [Tableau Public story.](https://public.tableau.com/app/profile/alejandra.rocha/viz/bikesharing_16780957266640/Bikesharing?publish=yes)

### **Checkout Times**
At the time this data was recorded, a 30 minute ride on a citibike cost 3 dollars for single-ride users. As can be seen on *Checkout Times for Users* below, most users checkout bikes well within in this 30 minute limit, for 5 to 15 minutes at a time.
![Checkout Times for Users](CheckoutTimes.png)


The heatmap below, *Trips by Weekday per Hour*, displays the busiest times for bike use. Weekends are busy from late mornings into the early evening. On the other hand, peak weekday usage is concentrated around morning and evening commuting hours. Taken together, this suggests that locals utilize the service to commute during the week and tourists utilize the service for leisure on the weekend. 
![Trips by Weekday per Hour](TripsByHour.png)
This is consistent with citibikes monthly operating report, which states that large transit and tourist hubs are the most popular origin and destinations. These are valuable insights into potential docking station location placement in a new city.

### **Women and Citibike**
Data about users' genders demonstrates a dramatic difference amongst citibike customers. Men make up 65% of users while women only make up 25%, although average checkout times are consistent across the spectrum. This is likely an extension of broader concerns about womens safety in public spaces. The heatmap below, *Trips by Gender (Weekday per Hour)*, makes this discrepancy between men and women usage unambiguous. 
![Trips by Gender](TripsbyGender.png)
*User Trips by Gender by Weekday* further illustrates the importance of gender as an indicator of use. Typical use patterns seen above become less significant when the data is filtered for women alone. Women are less likely to utilize the service as single-ride customers *or* subscribers.
![User Trips by Gender by Weekday](TripsbyGender_Weekday.png)
The consistency of checkout times across gender suggests people generally use the bike share service in the same way. This highlights an opportunity for improved service in a new city like Des Moines. By implementing more safety features on bikes and docking stations, more women might utilize the service.

## Summary
This information about citibike in NYC contains many valubale insights into its success, and how it can be improved upon in a new city. The service is primarily utilized by local commuters on weekdays, and casual single-ride customers on the weekend. Women are far less likely than men to use the service. Further analysis of this data would shed more light on usage patterns and operating costs. Such as visualizations that breakdown maintenance needs by customer types, and gender. In sum, the information represented in these visualizations makes a strong case for a bikesharing program in Des Moines.
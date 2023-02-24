# Bikesharing

[link to dashboard](https://public.tableau.com/app/profile/betsy.savage8513/viz/CitiBikeAnalysis_16771753288540/CitiBikeAnalysis?publish=yes)

## Purpose:

This project involved using Tableau to visually display charts and metrics from an imported data set. The specific data set of interest, Citibike ride information from NYC in August of 2019, was examined in order to gain insights about trends in customer ridership, usage patterns, ride duration, and ride start/end location. Ultimately, these observations are meant to inform a business proposal to establish a new Citibike market in Des Moines.    

## Overview of the Analysis: 

Because this analysis involved an examination of trip duration by customer segments, the initial step was to clean the csv to reflect an accurate data type for this column. The trip duration column was initially recognized as a string.

<img width="448" alt="image" src="https://user-images.githubusercontent.com/114873837/221055164-474f2e63-70c7-4390-a661-d96d00da56dd.png">

The original csv file was reformatted using pandas in jupyter notebook. 

<img width="777" alt="image" src="https://user-images.githubusercontent.com/114873837/221055321-c0d8e614-0d50-48c3-9515-c470a611bb68.png">

Once the csv was adjusted to reflect the trip duration in a usable date/time format, the updated file was imported into tableau to begin analysis and visualization of the data in order to gain insights about bike usage by geographic area, customer segments, and time of day.

## Results: 

### 1. Checkout Times for All Users

<img width="1161" alt="image" src="https://user-images.githubusercontent.com/114873837/221058398-0c26e00d-8752-4f63-9c03-700a01b00106.png">

Most bike rides are less than 40 minutes in length, and the most popular ride length is around 10 minutes.

### 2. Checkout Times by Gender

<img width="1170" alt="image" src="https://user-images.githubusercontent.com/114873837/221058450-8926b372-1d85-49c6-837e-5ebe7ea3aafa.png">

Male riders check out significantly more bikes for slightly longer ride times.

### 3. Trips by Weekday Per Hour

<img width="1184" alt="image" src="https://user-images.githubusercontent.com/114873837/221058513-0cfcf091-ecdc-41bc-84db-d673406db856.png">

Rides are most popular before and after working hours on weekdays (7-9am and 5-7pm). Rides are also popular between 10am and 5pm on weekends.

### 4. Trips by Gender (Weekday Per Hour)

<img width="1188" alt="image" src="https://user-images.githubusercontent.com/114873837/221058581-2a94ab3a-45cf-4b3e-94a7-a56f91897361.png">

Male riders are using more bikes between the hours of 6am-10am and 5pm-7pm on weekdays.

### 5. User Trips by Gender by Weekday

<img width="1182" alt="image" src="https://user-images.githubusercontent.com/114873837/221058665-3454703f-8946-4028-b41e-e2eefd84bb5f.png">

Ridership is heaviest among subscribers compared to non-subscribing customers. Of subscribers, male riders take more trips than their female counterparts.  Weekdays are the most popular time to ride, with Thursdays as the most popular day of the week.

### 6. Top Starting Locations

<img width="1182" alt="image" src="https://user-images.githubusercontent.com/114873837/221058095-1ba12225-5738-4830-b506-0db54881791d.png">

The city of Manhattan is popular for starting rides.

### 7. Customer Type

<img width="366" alt="image" src="https://user-images.githubusercontent.com/114873837/221058195-b53ee95f-c348-4865-891b-fecd66b3d69c.png">

More than three quarters of riders are Citibike subscribers.

## Summary: 

The graphs above can be summarized by the following:
1. Males comprise the majority of usage of the Citibikes. They ride most freqently before and after working hours on weekdays.
2. Most users of Citibikes subscribe to the service, and ridership is heavy among subscribers compared to non-subscribers.
3. Citibikes are often used for quick trips (around 10 minutes) around urban locations.

### Recommendations:

Based on these trends, I would make the following recommendations for the Des Moines market:
1. Market heavily to males, who are the target demographic.
2. Offer incentives, such as discounts, to become subscribers to Citibike, as subscribers will use the service most frequently.
3. In marketing materials, emphasize the potential for Citibikes to be used for commuting to and from work.

### Further Analysis:

Given the available data, I would make the following recommendations for further analysis:
1. Given the relatively lower usage rates among women, it would be helpful to identify more patterns around women riders. I would investigate what start/end stations are most or least popular for female riders. 
2. Similarly, it would be helpful to identify certain common traits among subscribers, since they are likely to use the service more frequently. I would include gender on the map of popular start/stop locations to investigate whether the subscribers are more common in particular neighborhoods.
3. Finally, external to this data set, it would be beneficial to accompany these results with a demographic map of Des Moines using the available census data in Tableau. A heat map showing the male population percentage in the greater Des Moines region would allow us to identify certain neighborhoods or districts where rider stations are most likely to be popular among the target demographic.

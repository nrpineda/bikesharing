# BikeSharing Business Analysis

## Overview

In the following presentation I used data retrieved from the Citi Bike System Data page to analyze the Citi Bike program in New York City.  The purpose of this analysis will be to implement the results to a business plan for the creation of a similar business model in the city of Des Moines. To do so, I used data visualizations created in Tableau, as well as the extraction, loading, and transformation of the data through Pandas. 

With this research I will answer the following questions:
	What kind of costumers does the Citi Bike program caters to?
	Is there a time of the day when there is an increment in usage?
  	Are there popular zones for bike-rental in New York City? If so, which are they?
	What are the demographics of the users of Citi Bike in New York City?

## Analysis

### Users Rendition

We first dive-in into a ‘Users Rendition’ to find out more about the costumers that Citi Bike in NYC currently caters to; the results are the following:

![Screenshot (73)](https://user-images.githubusercontent.com/111472338/213178044-be373afe-dfb9-4c90-a0ed-eec00b6b28a1.png)

For the single month of August, it was recorded that 1,900,359 (approx. 81.06%) of ‘Subscribers’ used the Citi Bike service, and 443,865 (approx. 18.94%) for ‘Costumers’. The users considered ‘Subscribers’ are those who frequently used the Citi Bike service. We also know that of all users: 1,530,272 (approx. 65.28%) identify as male; 588,431 (approx.25.10%) as female; and 225,521 (approx. 9.62%) as ‘other’ or ‘unknown’. According to the data, we also know that users of 54 years of age have the highest trip durations recorded (count of trip duration: 237,533 approx. 10.13%).  We can argue that age does not hinder the usage of bike-sharing services in the grand New York City. Furthermore, trip durations of users born in the years of 1986-1994 are also next to the highest count, surrounding those in the 1969 block. -This is a valuable finding as the median age of the Des Moines population is 35.2*, allowing a prediction of positive outcomes when taken age into account for a future bike-sharing business.

### Operations Research

Now that we have an idea of the type of costumer of NYC, we can analyze the results to the different times and zones of operation of Citi Bike. 

![Screenshot (74)](https://user-images.githubusercontent.com/111472338/213188806-0cce9ca7-9064-4ee1-8b5a-e848d638b018.png)

In the above visualization is shown the peak hours of usage with 5pm at a count of 224,566, and 6pm at a count of 215,783 (data retrieved from the starting time of all users). It may be an expected result as it is a peak hour for traffic as well; there are other factors that can also influence this increment: as a tourist, it may be a good couple of hours to catch the sunset, or for the locals to head back home after a day of work. Costumers in NYC may be taking all those factors into account and deciding to used the service, which is a good indicator for a similar business plan in Des Moines, as this service proofs to be used both in an utilitarian as well as a recreational way.

![Screenshot (76)](https://user-images.githubusercontent.com/111472338/213192121-74f63e50-db6a-426f-834c-7cd171f016b6.png)

Moreover, the map above depicts the zones with the locations with the highest counts as ‘Starting Points’ in the city. This is Manhattan, a very popular, very touristic area of New York. The same is true for the ‘Ending Points’ as shown in the map below:

![Screenshot (78)](https://user-images.githubusercontent.com/111472338/213194400-ef057534-3802-4f8c-9952-9f2385b367f8.png)

In both, the darkest and biggest points represent the highest number of counts per bike used. Applying this to the project in Des Moines, it is possible to make the prediction that the area of the State Capitol will need to have the most bikes accessible to the costumers and they will be put into use.

Along with the hours of operation, and most popular site to place accessible bikes; comes the maintenance that they will need.
We obtain this data by using each unique Bike ID and the number of bookings recorded for each one. Consider the following:

![Screenshot (79)](https://user-images.githubusercontent.com/111472338/213197986-5519f97f-04d3-4a3c-aea2-16266a65ad21.png)

With an increased amount of usage, naturally, there will be the expected wear-and-tear on the bikes. However, it must be considered as it is inevitable when planning on a specific number of bikes that will need to be purchased, strategically placed. 
Which bring us to the following question: What is the number of bikes booked per hour in a week?
The following heatmap shows the variants in numbers of bookings by the hour in each given day by all users:

![Screenshot (80)](https://user-images.githubusercontent.com/111472338/213200545-6f45371b-c31a-42b6-b671-099548486477.png)

As previously indicated, the hours with the highest usage range in between 5pm and 6pm; however, we can now see that this is happening more on Mondays, Tuesdays and Thursdays; representing with the darker shades on the daily blocks of the heatmap. This data was applied to the total of users. It also shows darker shades in between 8am - 9am. This suggests regular hours of commuting, reassuring its necessary nature for the costumers.

### Customer's Demographics

Next, we will visualize the customer’s usage by gender.

In the following line graph, we have extracted the number of users by the hour and their trip duration, broken down by gender. We can see that the largest count of users books a bike for a trip duration of 0-40 minutes approximately, and of those users, the highest peak represents male costumers at a high of 100K, while female users peak at roughly 33K, and unknown peaks at approximately 7K users. There is a significant number of male costumers checking out their bikes within one hour. There is a low but constant number of female costumers that check out their bikes after the first or second hour. 

![Screenshot (82)](https://user-images.githubusercontent.com/111472338/213207040-d2f58185-45a2-4433-8c37-28339c303964.png)

Furthermore, the following heatmap shows the user trips during the week by gender, classified under 'Costumer' and 'Subscriber':

![Screenshot (81)](https://user-images.githubusercontent.com/111472338/213209592-71594bd9-5180-435f-b6bc-20a85aaa02c4.png)

Supporting our previous findings, is depicted that the majority of users are male subscribers with a dense number of bookings during Thursdays with a highest of 259,316.

## Conclusions
The overall analysis of Citi Bike services in New York aimed to provide answers that will entice investors for a creation of a similar business model that will take place in Des Moines. The similarities shared with occupied metropolitan areas in these two cities, prove a potential success for a bike-sharing business. However, more research must be done to be able to reach female and unknown costumers in the city of Des Moines through a catered marketing campaign. Overall, this is an untapped market for Des Moines that awaits to be exploited, while also being beneficial to a very important economic aspect of the city, tourism. It is a safe, healthy, and environmentally conscious alternative way of commuting. Finally, this could be a project that would rapidly increase in popularity, allowing a margin of profit to happen rather quickly.


[link to dashboard](https://public.tableau.com/app/profile/rebeca.nuila/viz/NYCCitibikeAnalysis_16740435927430/NYCCitibikeAnalysis)

*Source :  https://www.populationu.com/cities/des-moines-ia-population#:~:text=The%20median%20age%20of%20the,years%20and%20over%20is%2036%2C996.

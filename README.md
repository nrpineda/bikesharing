# BikeSharing Business Analysis

## Overview

The following presentation used data retrieved from the Citi Bike System Data page to analyze the Citi Bike program in New York City.  The purpose of this analysis will be to implement the results to a business plan for the creation of a similar business model in the city of Des Moines. To do so, we used data visualizations created in Tableau, as well as the extraction, loading, and transformation of the data through Pandas. 

With this research we will answer the following questions:
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


*Source :  https://www.populationu.com/cities/des-moines-ia-population#:~:text=The%20median%20age%20of%20the,years%20and%20over%20is%2036%2C996.

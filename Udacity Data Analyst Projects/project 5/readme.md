# (Communicate Data Findings Report: Ford GoBike System Data)

## by (Bakut S Bonat)


## Dataset

Ford GoBike is a regional public bicycle sharing system in the San Francisco Bay Area, California. Beginning operation in August 29th 2013 as Bay Area Bike Share, the Ford GoBike system currently has over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. From it's early development, many other cities began adopting this system. This is the link for the dataset https://s3.amazonaws.com/fordgobike-data/index.html. This data set includes information about individual rides made in a bike-sharing system covering the San Francisco Bay area. Our goal as a data analyst, is to increase it's rideship and to offer deals through the mobile app. What deals can be offered? Currently, it has three options: a flat price for a single one-way trip, a day pass that allows unlimited 30-minute rides for 24 hours and an annual membership. In addition to using bicycles, Ford has introduced electric bikes called Ford GoBike Plus (ebike) https://www.fordgobike.com/how-it-works/meet-the-bike. 
 
The Data Structure are as follows: Each trip is anonymized and includes:

Duration Seconds
Start Time
End Time
Start Station ID
Start Station Name
Start Station Latitude
Start Station Longitude
End Station ID
End Station Name
End Station Latitude
End Station Longitude
Bike ID
User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
Member Birth Year
Member Gender
Bike share for all Trip
Member Age

## Summary of Findings

> After a preliminary wrangling of the dataset, exploration and assessing.

1. **Duration in seconds** averages 807 seconds, with explanatory analysis a need for Log transformation was used to figure out duration seconds less than 5000 records was 253962 records out of a total sample length of 256299 about 99.09% of the dataset,with a right skewed distribution.

2. **Duration in seconds by users** Subscriber users turned out to be the most users with over 200 thousand rides, interesting that the customer users take longer duration in seconds and riders whether they are subscriber or customer tend to have a similar duration in terms of age.

3. **Target Audience** based of the exploration above, knowing more about the users if the they are subscribers or customers, where subscribers tend generate more revenues with a good start knowing people hitting their 30's really love biking. Hence, the target audience where digital marketing can also increase number of subscribers.

## Key Insights for Presentation
>Duration In Seconds.
>Duration in seconds by users.
Target Audience.
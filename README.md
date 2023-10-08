# CityBikeTableau
Challenge18

# Background
Congratulations on your new job! As the new lead analyst for the New York Citi BikeLinks to an external site. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicise and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilisation. Each month, bike data is collected, organised, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

# Method & Result
Downloaded 12 months of JC citibike trip data (from Aug-22 to Jul-23).  Using July 2023 data to create the vizualisations.
Removed trips where the Ride ID did not end at a Station to ensure the vizualisations are taking into account valid start and end times.
![image](https://github.com/CRGMBC/CityBikeTableau/assets/134125287/23ea8d4f-d8c7-42b7-b732-2a2353298bf8)


Compared the Member rider vs Casual rider numbers per calendar day of July 23 (based on the start date)
Compared the Member rider vs Casual rider numbers per day of the week for the month on July 23 (based on start date) to see if there were variances to be used.  Noted that the Members were higher than non-members on all days of the week, but the casual riders were significantly higher on a Saturday & Sunday compared to a weekday.

Compared the Member rider vs Casual rider average trip length in minutes per calendar day of July 23 (based on the start date)
Compared the Member rider vs Casual rider average trip length in minutes per day of the week for the month on July 23 (based on the start date).  Members tend to take shorter rides than non-members.

Mapped there stations where the rides started, where the rides ended on background overlay map with Zip codes.
Mapped ending stations with the number of rides ending at a point as the colour & size marker.  This is on a background map where the median houshold income is displayed by colour to see if this shows an impact on the hiring.
Its interesting to note that majority of the rides ended back in Jersey citiy - the size of the markers in New York City are the smallest.  As expected, transport hubs have a high return rate.
![image](https://github.com/CRGMBC/CityBikeTableau/assets/134125287/0ed53c11-40b1-450a-b87c-f393fe03ad7a)




# Ford Go Bike Dataset Exploration
## by Ahmed Atta


## Dataset

> This data set includes information about more than 180000 individual rides made in a bike-sharing system covering the greater San Francisco Bay area on February 2019 , including duration , members gender , user type ,members birth year ,start and end time and other variables , the data can be found on https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv


## Summary of Findings

> In this exploration i made investigation mainly about the duration of bike rides and it's relation with other variables , The duration has a wide value range but most rides take short durations as observed from a high skewed graph ,and it became normaly distributed after i made a log trasformation of the duration. and i found that duration has a relation with day of week as duration average increase in weekends than other weekdays ,and i found out that customer type users tend to use bikes for longer durations than subscribers , and also duration has a strong relation with the birth year of members as members born after 1965 take the bikes for longer durations than others ,and when compared with hour of the day i found an interesting fact that when bikes using start from 2 to 3 am users use bikes for more duration in average , and males use bikes for less duration than females and others.

> After that i made a multivariate exploration to investigate if members gender have a relation with the durartion based on their birth year and i found out that despite females use bikes for longer durations than males in general but males have more age range and some of them ride bikes for longer durations than females and others.

> And finaly i found that each gender riding duration is related to the day of the week as males ride bikes for less time than Females on Monday , Thursday and Wednesday while Males uese bikes for longer periods on other weekdays , and finally Others use Bikes the fewest period of time everyday.


## Key Insights for Presentation

> In the presentation i focused on the impact of users characterestics on bike riding duration and i ignored the effect of riding start time and date.
> At first i ploted the distribution of riding duration after i made a log scale transformation followed by the distribution of members birth year and the Distribution of Member gender.
> Afterwards i presented a barplot for the user type against the duration average followed by a barplot for members gender against duration average.
> And finally i introduced a Facetgrid to show the relation between duration and birth year for each gender
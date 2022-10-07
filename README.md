# Ford GoBike System Data

## by Oluwanifemi Favour Olajuyigbe


## Dataset

The dataset consists of information of about 180 thousand trips made in February, 2019 in a bike-sharing system covering most of San Francisco Bay Area. It contains 16 features and can be found [here](https://www.google.com/url?q=https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv&sa=D&source=editors&ust=1663245935030396&usg=AOvVaw3IH3CKml-he8TtayfjFHZ0). However, after being properly cleaned, the data contained 174,391 ride information and 11 features. 


## Summary of Findings

This project had the goal of investigating factors that affect the duration of a ride and the time/period most trips are taken. From my analysis and explorations, I was able to find out the key attributes that first of all, had an impact on the duration of a trip and second, had an effect on the time a ride is started.

Findings on the factors that had an effect on trip duration
- A factor that had an effect on duration is time period of day. The trips that started at noon had the longest average trip duration.
- It was also observed that day of week had an effect on trip duration. Individuals had longer trips during the weekends, that is, Saturday and Sunday, than weekdays (Monday to Friday)
- Another main factor was user type. It was observed and proven in many explorations that customers had a longer trip than subscribers, regardless of whetever time of day, day of week or gender that might be involved.

Findings on the factors that had an effect on the time most trips are taken
- A factor was the day of the week. Most trips were taken during weekdays, with Thursday topping the chart with the highest number of trips started. Saturday and Sunday had the lowest turn up rate.
- The period of day was also an important factor. People mostly took rides in the mornings and evenings, but more in the evenings. Then, only a handful of people took rides in the late nights.
- More specific than the period of day that serves as another important factor is the hour of day. Most rides were taken in the hours of 8am and more at 5pm. Then the least trips were taken at 3am.

Outside of the main variables of interest, there were some interesting relationships I observed between member_gender and user_type, and age and user_type. There were more female and other gender customers than there were subscribers, and there were more male subscribers than there are customers, and then I noticed that the subscribers were slightly older than customers.

## Key Insights for Presentation

For the presentation, I focus on duration_min, start_weekday, start_period, start_hour, user_type. I start by answering one of the two questions, 'what time/period most trips are taken?'. I use the countplots of start_weekday, start_period, and start_hour.

Afterwards, I check the distribution of the duration_min, then go ahead to compare duration_min with start_weekday and user_type, respectively, and then compare the three, all the time using boxplots, to answer the second question, 'what factors affected the duration of the trip?'.


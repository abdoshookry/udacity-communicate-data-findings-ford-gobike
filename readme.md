# Ford Gobike Analysis

## by Abdelrhman Shookry

## Dataset

> This dataset is about Ford Gobike trips in feburary 2019.<br>
> there are 183,412 row in this dataset with 16 column (5 numeric, 8 string, 2 datetime and 1 boolean).<br>
> I will focus on the duration of each trip and it's relation with user type, gender, age , start and end stations.<br>
> the duration_sec is the most important feature and it's strongly related to the other features.

##### Wrangling :

- converting bike_share_for_all_trip to boolean.<br>
- converting start and end time to date time.<br>
- converting end and start station id and member birth year to string.

## Summary of Findings

- From Berry St at 4th St to San Francisco Ferry Building (Harry Bridges Plaza) is the most frequent trip.
- subscribers are more than the customers.
- most trip durations are lower than 7500 sec.
- the highest trip means were in days 10, 17, 23.
- customers tend to make longer trips.
- trip duration is dependent on the age.
- male trip duration is longer than female, and customer trip duration is longer than subscriber.
- customers have lower age than subscribers.

## Key Insights for Presentation

- most trips durations are between 300 sec and 1000 sec (around 8000 trip to 12000 trip) with beak 600 sec.
- most users are between 20 and 40 years old
- when the user is older the user tends to make shorter trips.

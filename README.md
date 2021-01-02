# Jersey City Citi Bike Analysis (2019)

![Citibike](images/citi_bike_logo.png "Citibike")

---

![Visualization](images/tableau_gif.gif "Tableau Visualization")

---

## Contact Information

Rob Savage 

rob.savage@me.com

[LinkedIn](https://www.linkedin.com/in/robsavage/)


[Tableau Public](https://public.tableau.com/profile/rob.savage)

---

## Project Description

The purpose of the project was to use the [data](https://www.citibikenyc.com/system-data) and make inferences and visualizations using Tableau.

---

## Tools Used

1. Python (Data Aggregation/Cleaning)

    - Pandas Library

2. Tableau (Visualization and Analysis)

3. Github (Publishing of Results and Analysis)

---

## Link to the Tableau Dashboard

- [Tableau Dashboard](https://public.tableau.com/profile/rob.savage#!/vizhome/tableau-homework_16055537229560/CitiBikeStory)

---

## Steps 

1. Used `Python` to aggregate/clean data from the [Citibike Data Page](https://s3.amazonaws.com/tripdata/index.html). The only files utilized were from Jersey City  in the 2019 calendar year. 

    - The `CSV` files in the `data` folder were uploaded to `Jupyter Notebook` using `Pandas`
    - The `starttime` columns were split, then moved over into their new respective columns `start time` and `end time`
    - The `starttime` columns were then subsequently dropped
    - The cleaned data frames were then exported as individual `CSVs` into the `cleaned` folder

2. Used `Tableau` to analyze the phenomena from the data by creating visualizations and dashboards

---

## Analysis

As COVID-19 has continued to ravage New York City, many residents have taken the opportunity to relocate to areas nearby that offer substantially more space for the new reality that has been thrust upon them. New Jersey has become a hot spot for those relocations and thus has become a focus of mine as we move into the new year. As the population continues to rise, I have taken data from 2019 to understand what potential trends we could see in the ‘New’ New Jersey in 2021, hopefully post-pandemic. These are those findings. 

### Bike Activity

Citi Bike has been able to carve out a substantial subscriber base in Jersey City, with subscribers making up the majority of user base. We see standard usage surges in the warmer months, especially during the summertime. During those same months, we also see a 150% increase in non-subscribers.  June-September serves as the hotbed for capturing new subscribers and should be treated as such.

### Gender Analysis

Males continue to be our most frequent riders. I looked at ride counts based on the time of day and gender and found very similar patterns. By far the most populous time of day is at 8am, followed by 6pm, which seems to indicate that a large portion of our rider base uses the bike for work transportation. For males, we see a slight elevation in ride count during lunchtime, as opposed to women who remain flat during that time period.

### Birth Year

The most prevalent age group within the rider base leans heavily towards Millenials. Much of that can be attributed to them being the prime workforce age at this point and time. One interesting piece of data that seems like an outlier is the overwhelming amount of riders born in 1969. Looking at the heatmap, I question the validity of the age since no other year in that age group shows up near that data point. I suspect the tongue-in-cheek nature of the year has skewed the data quite a bit. 


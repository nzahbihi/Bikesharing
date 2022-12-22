# Bikesharing
## Overview
The purpose of this analysis is to analyze New York City (NYC) Citibike data, specifically from August 2019, to aid in determining whether a bike-sharing program in Des Moines, IA could be successful.

## Resources
  * Data Source: [Citibike NYC Data](https://ride.citibikenyc.com/system-data)
  * Software: Tableau 22.2.1

## Results
The Tableau Story showcasing our analysis can be found [here](https://public.tableau.com/views/NYCCitiBikeDataVisualization_16627901911830/NYCCitiBikeDataVisualization?:language=en-US&:display_count=n&:origin=viz_share_link).

The first query we explored was peak hours for the time period we selected, August 2019. We sorted the number of rides by each hour of the day.
![Slide 1](https://user-images.githubusercontent.com/106129195/189473315-3e06ea2b-17c2-4df1-ac14-68d3b6d918a0.png)

We can see that between the hours of 17:00 to 19:00 (or 5:00PM to 7:00PM) are the peak hours of usage of the bikes. In contrast, the hours with the least number of rides were between 0:00 and 4:00 (or 12:00AM to 4:00AM).

The second query we investigated was the density of starting locations for the bikes. We wanted to visualize which areas of NYC the bikes are being started from.
![Slide 2](https://user-images.githubusercontent.com/106129195/189473442-474c6ec7-71a0-44f7-b5a7-f8fcdfba7f7d.png)

As the map shows, many bikes are being started from locations such as Manhattan and the Empire State Building, with less usage around areas such as Greenpoint and Williamsburg.

The third query was looking into how long bikes are being used versus the number of bikes being utilized.
![Slide 3](https://user-images.githubusercontent.com/106129195/189473498-6cdcf756-4742-49fc-95d2-3818f65f4494.png)

The chart shows that majority of the bikes are used for approximately 5 minutes, with fewer bikes being used for longer journeys.

The fourth query was similar to the third one, but we included data regarding gender of the users to visualize the usage of bikes among gender.
![Slide 4](https://user-images.githubusercontent.com/106129195/189473561-2abf4b69-39aa-4e8e-bb2c-9dbf1f4bd1c1.png)

According to this chart, men use the bikes the most, for 5 minutes. Whereas for women, they typically use the bike for 6 minutes. For the unknown category, the most amount of users used the bikes for 11 miuntes.

Our fifth query looked into trips by weekday, per hour. We wanted to see which days and times have the heaviest usage of bikes, as well as which days and times have the lightest.
![Slide 5](https://user-images.githubusercontent.com/106129195/189473723-6a38edae-f541-4127-8fcc-1c7ec8568634.png)

Displaying the data with a heatmap, we can see that Thursday mornings and evenings have the heaviest usage of the bikes. However, we can see that for Monday through Friday, the bikes are commonly used between 7:00AM to 9:00AM, and 4:00PM to 7:00PM.

The sixth query was similar to our previous one, but we included the data pertaining to the gender of the users.
![Slide 6](https://user-images.githubusercontent.com/106129195/189473790-e25ae6e4-8819-43ed-baf8-9434483d2598.png)

This heatmap shows that men utilize the bikes the most. This information correlates with the fourth chart, as shown above.

The final query we investigated for this analysis was trips by gender, by weekday and user type (customers and subscribers).
![Slide 7](https://user-images.githubusercontent.com/106129195/189473847-84ef13f9-2e29-4ae1-9456-0954facca0a5.png)

The chart shows that the customers' genders are relatively spread out. However, for subscribers, we can see that a majority of the subscribers are men, followed by women, then unknown.

## Summary
Our visualization of the NYC Citibike data has provided valuable insights into how the bike-sharing program is utilized. We can see that the bikes are commonly used in in the mornings and evenings Monday through Friday, but on the weekends, they're steadily used from approximately 9:00AM to 7:00PM. Thus, we could infer that the bikes may be used frequently in the mornings and evenings for people who are traveling to and from work using the bike-sharing program. This is backed up by our chart showcasing the user type and gender. Comparing subscribers to customers, we see that subscribers, who likely live in the area, use the bikes more often than customers, who are likely tourists.

We can also infer from the visualization that a high number of men use the subscription service, and make more trips compared to women and users in the unknown category. That being said, the trend of the day and hours of usage are similar across gender, as shown in the sixth chart.

Using these insights can be a valuable tool with assisting in potentially developing a bike-sharing program in Des Moines, IA. However, to further bolster our visualization of this data, there are other relationships within the data that we could evaluate. One such visualization could be the number of rides and the number of bikes. While Des Moines is a smaller city than New York City, it could give an idea of how many rides were taken with what number of bikes. This could bring perspective into costs of acquiring the bikes for the prospective program.

Another visualization could represent the names of the stations the bikes are being started from, and the total number of rides. This could be beneficial in pinpointing which areas the stations are located in, are more popular for the bikes. The information could be translated into pinpointing which areas in Des Moines would be best for setting up locations for the bikes.

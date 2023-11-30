# NewyorkcityBIKE using TABLEAU

ANAlYTICS: 

# Citi Bike Analytics

## Tableau Public Workbook
Link to Tableau Public Workbook: [Citi Bike Analysis NYC 2019-2020](https://public.tableau.com/app/profile/mauricio.andrews/viz/CitiBikeProgram_16981091046690/GendervsAge)

## Project Overview

As the lead analyst for the New York Citi Bike Program, I was tasked with building a set of data reports to answer critical questions about the program's utilization. The goal was to provide valuable insights to city officials for program improvement and publicity.

The initial stage of the project involved acquiring all the monthly CSV files, covering the period from January 2018 to December 2020, from the Citi Bike Data webpage and organizing them in a designated folder named "data". The data used in this analysis specifically pertains to the Jersey City region.

Subsequently, I established a Jupyter Notebook file, named "citibike.ipynb", to systematically clean and combine all the monthly CSV files into a single CSV file, in preparation for importing into Tableau.

## Data Exploration and Phenomena

### Total Trips Recorded
- Explored the dataset to determine the total number of recorded trips during the chosen period.

### Ridership Growth
- Calculated the percentage increase in total ridership over the selected time frame.

### Customer Type Changes
- Analyzed how the proportion of short-term customers and annual subscribers changed over time.

### Peak Hour Analysis (Summer vs. Winter)
- Identified the peak hours during summer and winter months when bikes were most frequently used.

### Station Analysis
- Investigated the top and bottom 10 stations for both starting and ending journeys. Provided hypotheses based on the data.

### Gender Breakdown
- Conducted an analysis of the gender breakdown of active participants (Male vs. Female).

### Gender Outreach Effectiveness
- Evaluated the effectiveness of gender outreach efforts in increasing female ridership.

### Trip Duration by Age
- Explored how average trip duration varied by age group.

### Average Distance Covered
- Calculated the average distance, in miles, that a bike was ridden.

### Bike Maintenance Recommendations
- Identified bikes (by ID) that were most likely due for repair or inspection based on usage patterns.

## Tableau Workbook Contents

- Created a Tableau Public workbook with 10 visualizations covering the phenomena mentioned above.
- Designed 2 dashboards for a comprehensive view of the data.
- Included a City Official Map for a geographic perspective of bike usage.
- Composed a Story to narrate the insights derived from the data.

**Insights Gained**

An evaluation of the data covering the time period from 2018 to 2020 shows a total of 1,095,641 trips made using bicycles in New York City. This represents a decrease of 4.83% over the three-year period. The observed decline in trips can be attributed to the adverse effects of the COVID-19 pandemic, including the associated shutdowns, on the usage of bicycles.

A comparison of the data from 2018 to 2020 reveals a decrease of 30.20% in the number of subscribers, while there was a simultaneous increase of 374.90% in the number of customers. This disparity in trends can be attributed to the impact of the COVID-19 pandemic on the usage of bicycles in New York City.

Over the specified time period, there appears to be a positive trend in the number of female riders, with an increase of 12.55%, while the number of male riders has decreased by 22.29%. While the reason for this trend is not definitively known, it could potentially be attributed to improved safety and security measures for female riders. Further analysis would be required to establish this hypothesis.

It is noteworthy that the peak utilization of citibikes in New York City occurs during the weekday, specifically during the hours of 8 a.m. and 5 p.m., as a significant number of commuters utilize bicycles for their daily commute.

A review of the data by month reveals that the highest usage of bicycles in New York City occurs during the summer months of July, August, and September, in comparison to the winter months. In April of 2020, a marked decrease in bicycle usage was observed, which can be attributed to the restrictions imposed during the early stages of the COVID-19 pandemic.

An analysis of the start station map highlights the concentration of the most frequently used stations in Jersey City, New Jersey, primarily in the zip codes 07302 and 07310. This suggests that the residents of Jersey City utilize the bicycle-sharing service extensively, potentially due to its cost-effectiveness when compared to other transportation options, such as taxis and ride-sharing services.

**Conclusion**
In conclusion, this Tableau analysis provides a comprehensive overview of the trends and patterns in Citibike usage over a specified time period. Through the creation of interactive dashboards and visualizations, key insights have been extracted and presented, highlighting trends in user type, gender, and age, as well as trip patterns based on hours and weekdays. One noteworthy phenomenon observed from the overall analysis is the high usage of the Citibike service by residents of Jersey City, New Jersey, primarily for commuting purposes. This analysis serves as a valuable resource for anyone interested in understanding the usage of Citibike and exploring the data behind this popular bike-sharing service. I hope that this work will inspire further research and investigation into the data, and encourage others to build upon the insights presented here.


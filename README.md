# NewyorkcityBIKE

ANAlYTICS: 

# Citi Bike Analytics

## Tableau Public Workbook
Link to Tableau Public Workbook: [Citi Bike Analysis NYC 2019-2020](https://public.tableau.com/app/profile/mauricio.andrews/viz/CitiBikeProgram_16981091046690/GendervsAge)

## Project Overview

As the lead analyst for the New York Citi Bike Program, I was tasked with building a set of data reports to answer critical questions about the program's utilization. The goal was to provide valuable insights to city officials for program improvement and publicity.

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


## Conclusion and Insights



The initial stage of the project involved acquiring all the monthly CSV files, covering the period from January 2018 to December 2020, from the Citi Bike Data webpage and organizing them in a designated folder named "data". The data used in this analysis specifically pertains to the Jersey City region.

Subsequently, I established a Jupyter Notebook file, named "citibike.ipynb", to systematically clean and combine all the monthly CSV files into a single CSV file, in preparation for importing into Tableau.

The following is a comprehensive overview of the data cleansing process:

First import pandas.
Screenshot 2023-02-13 at 4 46 14 PM
Read in all csv files for a single year in a pandas dataframe, store in a list, and then concatenate into a single dataframe.
Screenshot 2023-02-13 at 4 46 27 PM
Repeat step for the remaining years.
Screenshot 2023-02-13 at 4 46 35 PM Screenshot 2023-02-13 at 4 46 43 PM
Combine all three dataframes into a single dataframe.
Screenshot 2023-02-13 at 4 46 58 PM
Change the values in the gender column from the numerical value to the actual value.
Screenshot 2023-02-13 at 4 47 07 PM
Then save the dataframe to a csv file.
Screenshot 2023-02-13 at 4 47 14 PM
Please note that the large size of the CSV files precludes their storage in this repository and in GitHub's Large File Storage. As a result, the CSV files have been added to a .gitignore file.

Dashboards
From the Citi Bike data, a homepage and three corresponding dashboards were created to provide a comprehensive analysis and visualization of the data.

Homepage
The homepage serves as an introduction to the project, providing a concise overview of its purpose and contents. It clearly summarizes the key insights and findings of each dashboard, allowing for quick and easy navigation.
Screenshot 2023-02-13 at 8 21 56 PM

User Analysis
The dashboard presents a comprehensive analysis of the Citi Bike trips, taking into account various factors such as user type, gender, and age. Additionally, it provides an in-depth examination of trip patterns based on the hour of day and day of the week, as well as the total number of trips per month.
Screenshot 2023-02-13 at 5 32 45 PM

Station Analysis
The dashboard focuses on the analysis of trips in relation to the bike stations. It compares the trip patterns between weekdays and weekends and provides insights into the average trip duration for each month.
Screenshot 2023-02-13 at 8 22 32 PM

Geographic Analysis
The third dashboard features two maps showcasing the geographical locations of the start and end stations. The size and color of the markers are used to represent the total number of trips that originated or terminated at each station, providing a visual representation of the trip patterns and frequency.
Screenshot 2023-02-13 at 5 33 31 PM

A user-friendly interface has been created utilizing Tableau dashboards, allowing for seamless navigation between pages. Please access the link in the deployment section to explore the interactive dashboard and gain valuable insights.

Summary
Screenshot 2023-02-13 at 6 17 04 PM

An evaluation of the data covering the time period from 2018 to 2020 shows a total of 1,095,641 trips made using bicycles in New York City. This represents a decrease of 4.83% over the three-year period. The observed decline in trips can be attributed to the adverse effects of the COVID-19 pandemic, including the associated shutdowns, on the usage of bicycles.
A comparison of the data from 2018 to 2020 reveals a decrease of 30.20% in the number of subscribers, while there was a simultaneous increase of 374.90% in the number of customers. This disparity in trends can be attributed to the impact of the COVID-19 pandemic on the usage of bicycles in New York City.
Over the specified time period, there appears to be a positive trend in the number of female riders, with an increase of 12.55%, while the number of male riders has decreased by 22.29%. While the reason for this trend is not definitively known, it could potentially be attributed to improved safety and security measures for female riders. Further analysis would be required to establish this hypothesis.
Screenshot 2023-02-13 at 6 46 50 PM

It is noteworthy that the peak utilization of citibikes in New York City occurs during the weekday, specifically during the hours of 8 a.m. and 5 p.m., as a significant number of commuters utilize bicycles for their daily commute.
Screenshot 2023-02-13 at 6 56 45 PM

An examination of the data reveals that the pattern of peak bicycle usage in New York City remained consistent during 2018 and 2019, with the busiest periods occurring during the weekdays. However, in 2020, a notable deviation from this trend emerged, with weekends experiencing the highest levels of bicycle usage. This shift can likely be attributed to the widespread adoption of remote work as a result of the COVID-19 pandemic.
Screenshot 2023-02-13 at 7 05 26 PM

A review of the data by month reveals that the highest usage of bicycles in New York City occurs during the summer months of July, August, and September, in comparison to the winter months. In April of 2020, a marked decrease in bicycle usage was observed, which can be attributed to the restrictions imposed during the early stages of the COVID-19 pandemic.
Screenshot 2023-02-13 at 7 05 30 PM

The analysis of the data indicates that the majority of bicycle riders in New York City belong to the age group of 29 to 43, with a prevalence of male riders among this demographic.
Screenshot 2023-02-13 at 7 19 08 PM

An examination of the data reveals a disparity in the number of start stations compared to the number of end stations.
Screenshot 2023-02-13 at 7 19 16 PM

The analysis of the data, as depicted in the chart, indicates that Grove St PATH and Hamilton Park are the most frequently used stations for both starting and ending trips.
Screenshot 2023-02-13 at 7 19 20 PM

An examination of the graph presenting the average trip duration, measured in minutes, per month reveals a noteworthy increase in 2020 compared to the average trip durations in 2018 and 2019. This deviation can be attributed to the closure of businesses and an increased amount of time spent outdoors, particularly during the summer months, as a result of the COVID-19 pandemic.
Screenshot 2023-02-13 at 7 46 06 PM

An analysis of the start station map highlights the concentration of the most frequently used stations in Jersey City, New Jersey, primarily in the zip codes 07302 and 07310. This suggests that the residents of Jersey City utilize the bicycle-sharing service extensively, potentially due to its cost-effectiveness when compared to other transportation options, such as taxis and ride-sharing services.
Screenshot 2023-02-13 at 7 46 55 PM

Similar to the start station map, the end station map also illustrates a notable concentration of the most frequently used stations in Jersey City, New Jersey, indicating that residents are likely utilizing the bicycle-sharing service for their commutes to and from work.
Conclusion
In conclusion, this Tableau analysis provides a comprehensive overview of the trends and patterns in Citibike usage over a specified time period. Through the creation of interactive dashboards and visualizations, key insights have been extracted and presented, highlighting trends in user type, gender, and age, as well as trip patterns based on hours and weekdays. One noteworthy phenomenon observed from the overall analysis is the high usage of the Citibike service by residents of Jersey City, New Jersey, primarily for commuting purposes. This analysis serves as a valuable resource for anyone interested in understanding the usage of Citibike and exploring the data behind this popular bike-sharing service. I hope that this work will inspire further research and investigation into the data, and encourage others to build upon the insights presented here.

About
Citibike data analysis with Tableau

public.tableau.com/app/profile/jeremy.tallant/viz/citibike_16762569400730/Story1
Topics
python pandas tableau
Resources
 Readme
 Activity
Stars
 1 star
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Jupyter Notebook
100.0%
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact

The analysis revealed valuable insights into the utilization patterns of the Citi Bike Program. The visualizations and dashboards provide a clear and comprehensive view of the program's performance, allowing for informed decision-making and targeted improvements.

For a detailed analysis, please refer to the Tableau Public Workbook linked above.

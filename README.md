# PyBer Analysis
  Analysis of Ride Sharing data using Python, Jupyter and Pandas

## Overview of the analysis
Create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. Finally, submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.  The following reports will be produced:

- A ride-sharing summary DataFrame by city type
- A multiple-line chart of total fares for each city type
- A written report for the PyBer analysis
  
## Resources
- Data Source: city_data_csv and ride_data.csv
- Software: Python 3.7.6, Pandas and Matplotlib

## Results
The analysis of the Ride Sharing data show that:
  - Less urban cities have much lower of rides (by definition), but have even lowr number of drivers, which makes average Fare per Ride and especially Average Fare per driver be signicantly higher, as shown in the table below:
  
- Ride-Sharing Summary
![Ride-Sharing summary](/analysis/Ride_Sharing_DF.png)
  
 -  The total fare in urban cities are signifincatly higher than nom-urbans as shown in the chart below.  But this is mistly explained by higher number of rides, but not as much as total of drivers, as shown in the table above.
 
- Pyber-Fare Summary
![Pyber_Fare_Summary](/analysis/Pyber_Fare_Summary.png) 
 
  - The school summary was marginally affected to the downside, reinforcing suspicious activities on the 9th grade.  Average Math score was roughly unchanged at 83.4, Average Reading Score came from 83.8 to 83.9, % Passing Math from 93.3%to 93.2%, % Passing Reading from 97.3% to to 97.0 and % Overall Passing from 90.9 to 90.6.  The fact the the average did't have much impact and % Passing was lower makes us believe that only Non-Passing grades could have been altered, especially in reading.
  - However, the change on the scores was not enough to make Thomas High School loses the second position on Overall Passing Ranking.
  - Replacing the ninth-grade scores had the following impacts:
    - Math and reading scores were changed only to Thomas High Scholl 9th grades, all other grades and schools were unchanged as expected
    - Scores by school spending didn't have signicant changes
    - Scores by school size dindn't have signicant changes
    - Scores by school type didn't have signicant changes

## Summary

Major changes in the updated schoool district analysis were:

  - Thomas High School % Passing Reading came from 97.3 to 97.0
  - Thomas High School % Passing ath came from 97.3 to 97.2
  - Thomas High School % Overall Passing came from 90.9 to 90.6
  - Thomas High School Average Reading Score came from 83.8 to 83.9
  
The fact the the average scores were unchanged, and the % Passig Rate Decreased make us believe there are good chances in having alterations in the Non-Passing scores only, specially in readig.

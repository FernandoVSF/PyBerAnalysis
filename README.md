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
![Pyber_fare_summary](/analysis/PyBer_fare_summary.png) 
 
## Summary

Based on the results above, we have the following recommendations:

  - Although there are fewer rides on non urban cities, the number of drivers are not enough to support this demand.  Therefore the company should increase the bumber of drivers in those cities, which by consequence, have a higher compensation per ride.
  - As lower prices per ride ate correlated to higher number of rides, the copany should decrease the price in non-urban areas to increase demand.
  - By reallocating driver's to non-urban areas, there will be room to increase fares on urban cities, and inprove the break-even.

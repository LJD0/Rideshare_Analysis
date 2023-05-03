# Rideshare Analysis

### Overview

Ride share data analysis for Q1 2019.

### Resources

Software:

-VS Code 1.77.3
-Python 3.10
-Pandas
-MatPlotLib

Data:
resources/city_data.csv
resources/ride_data.csv

### Results

    This outlook focused on three main datasets, Total Rides, Total Drivers, and Total fares. all then broken down by city type to complete our analysis.

    Total Rides by city types
        Rural        125
        Suburban     625
        Urban       1625
    Total Drivers by City Type
        Rural         78
        Suburban     490
        Urban       2405
    Total Fares by City Type
        Rural        4327.93
        Suburban    19356.33
        Urban       39854.38

    Using this data we found the average fares per ride and driver

    Average fare per driver
        Rural       55.49
        Suburban    39.50
        Urban       16.57

    Average fare per ride
        Rural       34.62
        Suburban    30.97
        Urban       24.53


## Summary


Rides by City Type:

* Urban areas have the highest number of rides, indicating strong demand in densely populated regions.
* Suburban areas show a moderate number of rides, striking a balance between urban and rural characteristics.
* Rural areas have the fewest rides, reflecting lower demand in sparsely populated regions.

Total Rides, Drivers, and Fares:

* Urban areas have the highest number of total rides and drivers, indicating a thriving rideshare market.
* Suburban areas make a significant contribution to the overall market, while Rural areas have the fewest rides and drivers.

Insights from Charts:


Mean Rides by City Type (Boxplot): Urban areas exhibit a wider range and higher variability, reflecting fluctuating demand due to population density and transportation infrastructure.


Rides by Mean Fare: Rural areas have higher average fares, possibly due to longer travel distances and less competition. Urban areas have lower average fares, indicating a more competitive market.

<p float="left"> <img src="https://raw.githubusercontent.com/LJD0/Rideshare_Analysis/main/analysis/divers_by_city_type.png" width="30%" />



![drivers_by_city_type](https://raw.githubusercontent.com/LJD0/Rideshare_Analysis/main/analysis/drivers_by_city_type.png)



![rides_by_city_type](https://raw.githubusercontent.com/LJD0/Rideshare_Analysis/main/analysis/rides_by_city_type.png)



![fares_by_city_type](https://raw.githubusercontent.com/LJD0/Rideshare_Analysis/main/analysis/fares_by_city_type.png)


1. Percentage of Drivers by City Type (Pie Chart): Urban areas have the highest percentage of drivers, followed by Suburban areas, while Rural areas have the smallest percentage.
   
2. Percentage of Rides by City Type (Pie Chart): Urban areas contribute the largest share of rides, followed by Suburban areas, with Rural areas having the smallest proportion.
3. Percentage of Fares by City Type (Pie Chart): Urban areas generate the highest percentage of fares, followed by Suburban areas, while Rural areas contribute the least.
4. Weekly Fares by Date (Line Chart): Urban areas consistently generate the highest weekly fares, followed by Suburban areas. Rural areas have the lowest earnings, with fluctuations influenced by holidays, events, and weather conditions.

Conclusion:

* Urban areas have the highest demand, and rideshare companies should focus resources and marketing efforts accordingly.
* Suburban areas contribute significantly to the market and require tailored services.
* Rural areas have lower demand, and companies should assess feasibility and profitability.
* Peaks and dips in fare earnings highlight the importance of adjusting strategies to capitalize on peak periods and mitigate downturns.

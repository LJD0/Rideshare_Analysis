# Rideshare Analysis

### Overview

Ride share data analysis for Q1 2019.

### Resources Used

Software:
-VS Code 1.72.2
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

    The whole of this data was used to create a dataframe that was then formatted and plotted by fares by City Type across a timespan of four months, as shown in the Pyber_fare_summary PNG file

## Summary

    Total fares are made up heavily of urban fares. this would mean the majority of Pyber riders live in cities. A potential way to increase engagement in the less popular areas, suburban and rural, would be to give ride credit to or from more densely populated areas, while slightly increasing the fare the other way. Making the appeal seem better in the less popular areas to make travel plans with pyber.
    Another possible way to increase fares in rural areas would be by increasing drivers or driver pay in those areas. One potential reson rural areas cuould lack fares is lack of availability. Lastly It seems that while generally the trend of total fares is correlated, there area a few weeks in our summary that our city types values rise and fall independently. Within those weekly time frames offer flash deals and early purchase discounts that allow drivers and customers to benefit all while increasing the total fares for those offset times.

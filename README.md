# PyBer_Analysis_Challenge
## Project Overview
After completing an extensive analysis of the ride sharing service PyBer's data their management team has requested an additional study.  PyBer has requested a summary analysis based on merging their city reference data with their ride details.  Additionally, a multi-line graph displaying total weekly fares by city type for the first four (4) months of the year will be provided.

## Resources
  * Two Input csv files were provided by PyBer: 
    * city_data.csv - details on each city including type, driver count, and city name.
    * ride_data.csv - details on each ride including city name, timestamp of the ride, fare, and ride id.
  * Software: Python 3.7.9, Jupyter Notebook 6.1.4, pandas 1.1.3, matplotlib 3.3.2, Git Bash 4.4.23

## Results Analysis
An analysis of the [Pyber Summary Metrics](https://github.com/goldbala55/PyBer_Analysis_Challenge/blob/main/analysis/PyBer_summary_metrics_by_city_type.png) has provided the following insights: 

    * Rides, Drivers, Total Fares:
      * Urban total rides were 2.5 times as large as Suburban and 13 times as large as Rural.
      * But, given Urban drivers out number Suburban and Rural drivers by a factor of 5 and 31 times respectively, this is not a strong showing for the Urban business.
    * Average Fare per Ride and Driver
      * Suburban and Urban drivers significantly outperform Urban drivers in per ride and per driver averages.
        * Compared to Urban drivers, Suburban drivers outperform and generate 21% larger fares per ride and 58% larger fares per driver.
        * Compared to Urban drivers, Rural drivers excelled with 29% larger fares per ride and 70% larger fares per driver.

However, a historical trend review of [Pyber Total Fare by City Type](https://github.com/goldbala55/PyBer_Analysis_Challenge/blob/main/analysis/PyBer_fare_summary.png) clearly demonstrates that the Urban business consistently generates the overwhelming majority of the monthly revenue dwarfing the total of urban and suburban monthly revenue.
## Summary Recommendations
After reviewing the results of the follow up analysis I recommend PyBer management:
1. Start a recruiting campaign to increase the number of Suburban drivers.  This is the best intersection of available new drivers and population to support more rides.
2. Start an advertising campaign geared to Suburban areas to increase ridership.
3. Perform a marketing survey to determine how much latent demand there is in the Rural market before making further investments.
4.  Perform a detailed analysis of Urban driver performance and weed out the lower performing drivers.
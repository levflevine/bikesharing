# Bikesharing

## Overview of the Analysis

### Purpose

The purpose of this project is to create a data-driven proposal to an angel investor on how the bikesharing business may work in Des Moines, Iowa. The angel inverstor might be intersted in providing seed funding to explore a bike sharing program, but needs a detailed analysis to make their decision. The project delivers data analysis of the bikesharing business based on a dataset from the Citi Bike program run in New York City. 

### Approach

For this analysis, Pandas was used to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, a set of visualizations in Tableau was created to:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week
- Create a final presentation and analysis to pitch to investors.

### Deliverables: 

1. Change Trip Duration to a Datetime Format
2. Create Visualizations for the Trip Analysis
3. Create a Story and Report for the Final Presentation

### Tools and Data Sources

#### Tools

- Python Scripts
- Jupyter Notebook
- Pandas Library
- Tableau

#### Data Sources

- [Citibike System Data Page](https://www.citibikenyc.com/system-data)

## Results

### Published Tableau Analysis

[https://public.tableau.com/app/profile/lev.levine/viz/NYC_Citibike_Challenge_16397783439880/Bikesharing_Story](https://public.tableau.com/app/profile/lev.levine/viz/NYC_Citibike_Challenge_16397783439880/Bikesharing_Story)

### Checkout Times

- Majority of the bike trips are under 30 minutes long
- Average bike usage per trip is approximately 15 minutes

![Checkout Times](/Resources/checkout_times.png)

### Checkout Times by Gender

- Both, male and female bike riders demonstrate similar bike usage per trip
- Average ride is approximately 15 minutes long for males and females

![Checkout Times by Gender](/Resources/checkout_times_by_gender.png)

### Trips by Weekday

- On workdays, largest number of trips occur between 7 and 9 am and between 5 and 7 pm
- The busiest day for trips is Thursday
- Wednesday evenings are less busy than other workday evenings
- On the weekends, the busiest ride time is between 10 am and 5pm

![Trips by Weekday](/Resources/trips_by_weekday.png)

### Trips by Gender

- Both, male and female bike riders demonstrate similar bike usage behaviors by weekday and time

![Trips by Gender](/Resources/trips_by_gender.png)

### Trips by Gender by Weekday

- Subscribers use the bike service much more frequently
- The busiest day for subscribers is Thursday
- Non-subscription customers demonstrate higher usage of the bike service on the weekends for both males and females
- Male and female users demonstrate comparable behaviors by weekday and by user type

![Trips by Gender by Weekday](/Resources/trips_by_gender_by_weekday.png)

### Top Starting Locations

- Top locations to start bike riding trips in NYC: High School, Grand Central Terminal, Union Square (market, cafes, stores, and artists), Ferry Terminal, River bank, Central Park, and New York Penn Station

![Top Starting Locations](/Resources/top_starting_locations.png)

### Top Ending Locations

- Top locations to end bike riding trips in NYC: High School, Grand Central Terminal, Union Square (market, cafes, stores, and artists), Ferry Terminal, River bank, Central Park, and New York Penn Station

![Top Ending Locations](/Resources/top_ending_locations.png)

### August Peak Hours

- The lowest usage of the bikes is between 2 am and 4 am. 
- The peak usage is between 4 pm and 7 pm and around 8 am. 

![August Peak Hours](/Resources/august_peak_hours.png)

### Customers

- 81% of users used subscription
- 19% of users used the pay-as-you-go model

![Customers](/Resources/customers.png)

### Gender Breakdown

- 65% of bike riders in NYC are males
- 25% of NYC bike riders are females


![Gender Breakdown](/Resources/gender_breakdown.png)

## Summary

### Summary of the Results

**Product Marketing:**

    - For the existing business in NYC, the female population is the main growth opportunity => create marketing campaign focusing on females
    - For the greenfield business in Des Moines, initial customer base is likely to be predominantly males => focus the marketing campaign on male users to accelerate building the initial customer base
    - High subscription rate has a positive impact on the business: better predictability of demand, recurring revenue streams, and customer loyalty => prioritize marketing the subscription service

**Characteristics of the most popular bike riding trip starting and ending locations:**

    - Proximity to mass transit / transportation hubs
    - Proximity to tourist and major shopping and cafe attractions
    - Areas with high population density and traffic challenges
    - Areas with high number of office spaces / high number of commuting employees
    - Proximity to parks
    - Proximity to high schools

**Bike Usage:** 
    - Average bike usage per trip is approximately 15 minutes
    - The lowest usage of the bikes is between 2 am and 4 am. This is the best time for bike maintenance
    - The peak usage is between 4 pm and 7 pm and around 8 am. Consider variable pricing based on time of day (and weekeday) to shave off the peak demand for the bikes and get more riders during off-peak hours.

### Additional Analyses and Visualizations Suggested for the Next Phase of the Project

1. Bike usage based on district population density (number of bikes to cover the number of people living in and visiting each district)
2. Financial Analysis: subscription and pay-as-you-go pricing per user, ride volumes by month, and capital & operational expenses to launch and operate the project
3. Seasonality of the bike demand: it is likely that in winter months, the bike operation is on hold or substantially reduced, which will have a major impact on the business case
4. Bike maintenance data - how frequently the bikes are serviced and the related costs

# Bike Sharing

## Purpose

Perform a bike trip analysis based on the results of available information from NYC.
1. Will need to convert csv file's "tripduration" column to a datetime datatype.
2. Create Visualizations for the trip analysis.
  - Checkout times for users
  - Checkout times by gender
  - Trips by Weekday for each hour
  - Trips by gender (weekday per hour)
  - Trips by gender by weekday
3. Create a story and report for final presentaiton.

## Results

1. CSV file's tripduration" column was converted to a datetime datatype.

[IPYN_File](https://github.com/nkinsler/bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb)


2. Visualizations
  a. Checkout times for users
  
  ![Checkout times for users](https://github.com/nkinsler/bikesharing/blob/main/Resources/Checkout%20time%20for%20users.png)!
  
  The bulk of users checkout time is trips under 30 minutes in length.  Most of the users cehckout times are for five minutes.
  
  b. Checkout times by gender
  
  ![Checkout times by gender](https://github.com/nkinsler/bikesharing/blob/main/Resources/Checkout%20time%20by%20gender.png)!
  
  The bulk of users checkout time is trips under 30 minutes in length.  Most of the users cehckout times are for five minutes.  Significantly more males checkout bikes as compared to females and unknowns.  The usage follows the same pattern where the bulk of usage is for 30 minutes or less.
  
  c. Trips by Weekday for each hour
  
  ![Trips by Weekday for each hour](https://github.com/nkinsler/bikesharing/blob/main/Resources/Trips%20by%20weekday%20per%20hour.png)!
  
  The concerntration of bike usage during weekdays are between 8am and 9am as well as 5pm to 7pm.  This would indicate that bike usage is heaviest when users are trying to get to and from work.  On weekends, the usage tends to be more conssitent from 9am to 7pm with higher usage on Saturday.
  
  d. Trips by gender (weekday per hour)
  
  ![Trips by gender](https://github.com/nkinsler/bikesharing/blob/main/Resources/Trips%20by%20gender.png)!
  
  The concentration of bike usage is the same as the trips by weekday for each hour analysis.  Results indicate higher usage by males during the smae times listed above.
  
  e. Trips by gender by weekday
  
  ![Trips by gender by weekday](https://github.com/nkinsler/bikesharing/blob/main/Resources/User%20trips%20by%20gender%20by%20weekday.png)!
  
  Results indicate hihger usage by males with higher concentration on Thursdays and Fridays.  Female usage seems to be more consistent throughout the week with lower usage on Wednesdays and Sundays.
  
  f. Top starting locations
  
  ![Top starting locations](https://github.com/nkinsler/bikesharing/blob/main/Resources/Top%20starting%20locations.png)!
  
  Higher usage for starting locations are located around subway stations and points of interest.
  
  g. Top ending locations
  
  ![Top ending locations](https://github.com/nkinsler/bikesharing/blob/main/Resources/Top%20end%20locations.png)!
  
  Higher usage for ending locations are located around subway stations and points of interest.  The similarities between starting and ending location concentrations indicate that users tend to rent bikes agains to get back to their original locations.

## Summary

[Link to dashboard](https://public.tableau.com/app/profile/nicholas.kinsler/viz/bikesharingchallenge_16645629353590/NYCBikeSharing?publish=yes)

### Overall Summary

NYC bike sharing relies heavily on subscribers.  Subscribers are mostly using for getting to and from work.  Customers outside subscribers are using on weekeneds possibly to tour major tourist areas.  In order to apply to Des Moines, will need to assess the subscription base in the area.  Reaching out to local businesses will lead to higher success rate and ability to properly assess drop off points for the bikes.

### Additional Visualizations
1. Price per Trip - Know how much you are receiving for each trip on average.
2. Cost per Trip - Know costs per trip on average.

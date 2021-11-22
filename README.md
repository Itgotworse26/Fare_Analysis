# Fare_Analysis
Challenge assignment for Module 5

VIsualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Overview of the analysis:
The purpose of this analysis is to conduct an analysis of fares and break them down by the type of community they are run in. For this project, Omar and I will have to write some matplotlib codes to organzize the fare data by city type and analyze how they run over the course of January to December.  

## Results:

![Analysis of Fares by City Type](https://github.com/Itgotworse26/Fare_Analysis/blob/main/analysis/city_type_summary_df.png)

* As seen above, urban cities have the highest count of rides (1625 rides), most drivers (2405 drivers), and highest total fares ($39854.38). However, the average fare per ride ($24.54) and fare per driver ($16.57) are the lowest, meaning that not only do urban drivers make the least per fare, PyBer makes the least fares per ride in urban cities.

* While suburban cities only have the second highest count rides (625 rides), drivers (490 drivers), and only reach second place with their total fares ($19356.33), their average fare per ride ($30.97) and fare per driver ($39.50) are the second highest. 

* Even though rural cities have the lowest count of rides (125 rides,), least drivers (78 drivers), and lowest total fares ($4327.93), the average fare per ride ($34.62) is the highest and drivers make the most money per fare ($55.49).


![Analysis of Fares over Jan to April](https://github.com/Itgotworse26/Fare_Analysis/blob/main/analysis/PyBer_fare_summary.png)

* Urban total fares are the highest; it is only during the beginning of the year and one small period in March do they fall below $2000. The very start of the year is the lowest point for urban total fares while the high points are in the tail end of February and start of March.

* Surburban total fares are the second highest. Like the urban total fares, the start of the year is the lowest point, with long stretches of total fares barely staying above $1000. The high point for surburban total fares comes in the tail end of February with another brief spike at the end of April.

* Rural total fares are the lowest. The lowest point for rural total fares is in the beginning of January, but they remain consistently low. It is only at their highest point at the beginning of April when rural total fares make it to $500. 

## Summary:
Even though the highest total fares comes from the urban area, PyBer makes more per fare in rural areas. Drivers in rural areas also make more per fare as well. While this does not mean much in terms of total fares, it does represent how PyBer might adjust its strategy in non-urban areas. 

If PyBer wants to figure out how to increase profits, one of the best ways to do so at face-value is to increase the number of rides without increasing the number of drivers throughout all areas. Of course, the problem would be the possibility that the quota implemented on existing drivers would be unrealistic and lead to bad publicity and liabilities, especially if said drivers get into accidents on company time. 

A more optimal method would possibly be increasing the number of drivers and rides in rural and suburban areas. As pointed out, even though total fares in rural and surburban cities are lower than in urban areas, PyBer makes more per fare and drivers make more per fare as well. Asking for more rides from existing drivers would be a legal and logistical debacle, but if PyBer attracts more drivers in rural and surbuban areas by pushing the angle on how much rural  surburban drivers make per fare, it can then adjust for strategies that can then attract more riders in rural and surburban areas. The advantages non-urban areas have in fares per ride might not survive, but the potential for higher total fares could be worth the trade-off. 

Another angle PyBer should look at is increasing ridership in the months where fares dropped; periods of March in urban areas, the end of February to the middle of March in suburban areas, and almost the the entire four months in rural areas. By keeping ridership up with special offers for both new and existing riders, PyBer can maintain the fare per ride advantage that non-urban drivers have over urban drivers; a neccesity if PyBer wants to increase drivers and thus, rides in non-urban communities. 
This project analyzes and forecasts daily passenger traffic for different public transport routes.

Dataset : Local Route, Light Rail, Peak Service, Rapid Route, School, Other 
Total records=1918

Preprocessing :

1 identifying null values 
2 replacing using median
3 converting data column into date format and setting it as index

Features
1 calculated total traffic
2 computed ratios for each route
3 calculated lag features for each route
4 added day related features like is weekend

Algorithm

Random Forest Regressor
1 it handles multiple features
2 captures non linear relationships between features
3 robust to outliers

Output
To forecast 7 days for all the routes

Key insights

1.Light Rail and Rapid Route show the highest contribution across most days.

2.Local Route, Light Rail, and Rapid Route show a strong positive correlation, indicating that they rise and fall together.

3.When school routes are active, the system experiences more than double the total traffic compared to inactive days.

4.Traffic is lower on weekends compared to weekdays

5.Rapid Route traffic experiences the largest fluctuations indicator of peak travel days

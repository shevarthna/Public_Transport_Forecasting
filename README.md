This project analyzes and forecasts daily passenger traffic for different public transport routes.

Dataset : Local Route, Light Rail, Peak Service, Rapid Route, School, Other 
Total records=1918

Preprocessing :

1.Identifying null values 

2.Replacing using median

3.Converting data column into date format and setting it as index

Features:

1.Calculated total traffic

2.Computed ratios for each route

3.Calculated lag features for each route

4.Added day related features like is weekend

Algorithm:

Random Forest Regressor

1.It handles multiple features

2.Captures non linear relationships between features

3.Robust to outliers

Output:

To forecast 7 days for all the routes

Key insights:

1.Light Rail and Rapid Route show the highest contribution across most days.

2.Local Route, Light Rail, and Rapid Route show a strong positive correlation, indicating that they rise and fall together.

3.When school routes are active, the system experiences more than double the total traffic compared to inactive days.

4.Traffic is lower on weekends compared to weekdays

5.Rapid Route traffic experiences the largest fluctuations indicator of peak travel days

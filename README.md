# New-york-city-taxi-trip-duration
The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published 
by the NYC Taxi and Limousine Commission (TLC).
We are tasked with creating 2 models to predict the duration of the trip(time in sec) for test dataset. dataset source :https://www.kaggle.com/c/nyc-taxi-trip-duration/data

Distance Calculation:

Here we will calculate the distance between the pickup and dropoff coordinate using Haversine Formula. Haversine:
The haversine formula determines the great-circle distance between two points on a sphere given their longitudes and latitudes. Important in navigation, 
it is a special case of a more general formula in spherical trigonometry, the law of haversines, that relates the sides and angles of spherical triangles. 
For the Haversine formula, we need coordinates in radians.So we use radians method of numpy for the conversion from degrees to radians.

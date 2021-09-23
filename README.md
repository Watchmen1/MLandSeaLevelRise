# MLandSeaLevelRise

I.  Data Assembly 

Here the data was taken from the files downloaded from our various sources(mostly NASA) and read into data frames using pandas. I then merged the data and cleaned it up a bit. Finally since the sea-level data was taken over a different time interval than the data from the other two (antarctica and greenland ice sheets data), I tried to pick out overlapping dates over our desired range of time, and select them out of the over all data frame.

II. Linear Regression Model

Here I built and ran a more simple linear regression model on the data just to give an effective comparison for the next step where I trained the Neural Network Regression model. Didn't use this in our final presentation, but again it was mainly just useful to compare how well our Neural Network performed.

III. DNNRegressor Model

In the final step I trained our DNNRegressor model from the TensorFlow package with our data, and then tried to measure how effectively it was able to fit the data.

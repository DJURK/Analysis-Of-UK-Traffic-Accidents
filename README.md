# Analysis-Of-UK-Traffic-Accidents

In this project, I looked at about 1.5 million car accidents in the UK since 2005.

I had two goals for this project - to create a visual dashboard for the information, and to create a model that could predict daily counts of accidents at the city level.

I used bokeh in Python to create a zoomable visualization of all the accidents, and Tableau to create a dashboard that could be used to filter accidents in various ways.

In terms of modelling, I attempted to create an ARIMA time series, but the results didn't uncover any significant temporal trends.  I then engineered my data to put it in an easy machine learning format, and used an XGBoost regression model to make predictions.

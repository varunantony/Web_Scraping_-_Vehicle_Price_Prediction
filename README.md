# Web_Scraping_-_Vehicle_Price_Prediction
In this notebook, I scrape autotrader.co.uk for vehicle data like Price, Mileage, Model Year, Model Name, and Dealer Type to build a regression model to predict vehicle prices on Rolls-Royce vehicles. 

I used BeautifulSoup, urllib to scrape the website for 205 vehicle data-points. I then used TensorFlow and Scikit Learn for modelling the data to predict price of vehicle.
I introduced feature_crosses as a feature-engineering measure but found the results to be mixed. The best performance of RMSE Euro 29,900 and R2 of .86 was attained using scikit-learn
with only 16 features. 

The features grew from 4 to 16 due to one-hot encoding of the 4 features, present as string/text, and creation of 2 additional features using feature_crosses.

# CarPricePrediction
Old cars price prediction from ebay.com

The data has been derived from the ebay website.
It has following features
dateCrawled : when this ad was first crawled, all field-values are taken from this date
name : "name" of the car
seller : private or dealer
offerType
price : the price on the ad to sell the car
abtest
vehicleType
yearOfRegistration : at which year the car was first registered
gearbox
powerPS : power of the car in PS
model
kilometer : how many kilometers the car has driven
monthOfRegistration : at which month the car was first registered
fuelType
brand
notRepairedDamage : if the car has a damage which is not repaired yet
dateCreated : the date for which the ad at ebay was created
nrOfPictures : number of pictures in the ad (unfortunately this field contains everywhere a 0 and is thus useless (bug in crawler!) )
postalCode
lastSeenOnline : when the crawler saw this ad last online


I have performed data cleaning, imputes the missing values and treated the outliers of the data which affect the accuracy scores. 
The following regression models were used to find the best accuracy score. 
Linear Regression
SGD Regressor
KNN regressor
Ridge and Lasso regressor 
SVM regressor
Decision tree and random forest

The R sqaure improved from .53 to .80


Link to the dataset : https://www.kaggle.com/orgesleka/used-cars-database

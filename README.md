# BasketballLeague-POTM-Predictor
This model consists of web scraping the data and applying a regression model.
The dataset range has to be updated according to the range of league competitions to make predicitions.
This model calculates the next Player Of The Match for the Basketball League on the grounds of the data web scraped from the stats reference site ranging from the years 1991 to 2021.
Beautiful Soup is used to parse the HTML files present at the location with gathering relevant awards data.
NOTE : PLEASE CHECK THAT TO AVOID TIMEOUT BY THE WEBSITE PROVIDE SUFFICIENT TIME.SLEEP(INT) VALUE IN BETWEEN REQUESTING THE SITE FOR DIFFERENT DATASET.
Selenium is used to implement the Chrme Web Driver utilised to reduce manual interference and to automate the process of Data Scraping.
NOTE: KINDLY CHECK THE SELENIUM DRIVER WEB VERSION ON YOUR DEVICE.

THE MODEL USES A SET OF PREDEFINED PREDICTORS AND A REGRESSIO BASED MODEL IS APPLIED TO CALCULATE THE RESULTS.
IN THE FINE TUNED MODEL, 40 FEATURES AS PREDICTORS ARE FED AS AN INPUT TO THE
RANDOM FOREST REGRESSION MODEL WITH NO. OF ESTIMATES EQUAL TO 70.
THE MEAN_ACCURACY_PREDICTION RANGES FROM 89.2% FOR MODEL AND AROUND 80.1% DURING THE BACKTEST STEP.



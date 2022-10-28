# Stock Investments using Machine Learning

### San Jose State University DATA 240 - Data Mining Project from Sep 2021 - Nov 2021

---
##### This project contains code and project report for a new way to approach stock predictions
---

### Project Description
The project goal for the class was to utilize data mining techniques on machine learning model outcomes as well as demontrate feature reduction and generation. The purpose of this approach is to reimagine the use of machine learning to predict stock prices. The models will be trained on a single stock and data mining will be utilized to attempt to maximize financial gains and minimize risk. This could be useful for investors who want a chance to successfully complete a sell limit order which will sell stock once a certain price is reached. Instead of the traditional numerical predictions, these models will be binary for "buy" and "don't buy".

### Datasets
##### Tesla Stock Data from Yahoo Finance
https://finance.yahoo.com/quote/TSLA?p=TSLA&.tsrc=fin-srch </br>
The dataset being trained on is the TSLA stock prices from 6/29/10 to 11/19/21. The dataset was manually downloaded from Yahoo and contains a selection of information including open, high, low, close prices, as well as adjusted close price and trade volume.

### Files in Repository
##### Stock Classification Notebook.ipynb
This file contains and organized python notebook for most of the coding for the project. GridSearchCV steps and other minor data exploration is ommited. Otherwise, the notebook contains data preparation, modeling, and predictions on a smaller test dataset.

##### DATA240 - Final Report.pdf
This file contains the final report for the DATA 240 - Data Mining course at San Jose State University. It contains a more thorough explanation of each of the steps and results for the notebook. Finally, it contains the background information and reasoning for steps taken.

##### TSLA.csv
This file contains training and testing data that spans from 6/29/10 to 10/22/21. The columns include open, high, low, close prices, as well as adjusted close price and trade volume.

##### TSLA Predict.csv
This file contains example prediction data that spans from the dates 08/23/21 to 11/19/21. However, only 10/19/21 to 11/18/21 will contain predictions. Other dates are used to calculated moving averages.

### Future Work
This section is dedicated to listing out future submissions into GitHub as well as proposed improvements to predictions, models, or visualizations.

* Include other models such as SVM or nueral networks
* Create a user interface that streamlines the process and include error checking
* Change the data input into an API that fetches stock data for quick and easier predictions


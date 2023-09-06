# Predicting Bundesliga Match Results

In this project, our aim is to build a machine learning model to predict match results in Bundesliga, Germany's primary football league.

We first scrape data from [http://fbref.com](http://fbref.com) using Requests, BeautifulSoup and Pandas, and create a csv file containing match logs over six seasons.

After cleaning and getting our data set ready for machine learning, we build models predicting who will win a match using Scikit-Learn. 

We compare performances of k-nearest neighbors, random forest, ridge classifier and support vector classifier algorithms on our data set using time series cross validation.
# Predicting Bundesliga Match Results

In this project, our objective is to build a machine learning model to predict match results in Bundesliga, Germany's primary football league.

We begin by gathering data from [http://fbref.com](http://fbref.com) utilizing the Requests library for web scraping, BeautifulSoup for parsing HTML, and Pandas for data manipulation. This data is then stored in a CSV file containing match logs spanning six seasons.

Subsequently, we clean and preprocess our dataset to ensure it is ready for machine learning analysis. Using the Scikit-Learn and XGBoost libraries, we construct predictive models aimed at determining match winners.

We employ a range of classifiers, including random forest, ridge, support vector machines, and xgboost classifiers, and evaluate their performance using time series cross-validation.

Furthermore, we investigate how including rolling averages of recent match performance metrics and the number of days since the team's last match impacts model performance.

Throughout the project, we perform grid search using the F1 score as the main metric to optimize our models. Additionally, we note the accuracy and ROC AUC scores for each model, and plot ROC curves, allowing us to visually compare their fits.
# ZM_Portfolio
Data Science Portfolio

# [Project 1 - 2021 Stack Overflow Survey Salary Prediction Model](https://github.com/zmalone91/Developer_Salary)

* Data from the 2021 Stack Overflow Annual Developer Survey - https://insights.stackoverflow.com/survey
* Interactive web app using streamlit to predict Developer salaries based on input criteria of country, education level, and years of coding experience..<br>
* The Jupyter notebook includes the data preprocessing and cleaning process as well as an evaluation and grid search of Regression algorithms.<br>
* The model with the best score-to-resource consumption ended up being a Decision Tree Regressor with max_depth = 10. Linear regression, polynomial regression, L1 Lasso, L2 Ridge, and Random Forest regressors were all evaluated but Decision Tree ended up being the most suitable choice.<br>
<img width="593" alt="Salary_Predict_1" src="https://user-images.githubusercontent.com/34782953/141933850-a99b2d78-a484-41a1-9911-5ab3c3d4a9f9.png"><br>
<img width="542" alt="Salary_Predict_2" src="https://user-images.githubusercontent.com/34782953/141933865-d248a219-0cf7-40bf-9db2-65d153971887.png"><br>
<br>

# [Project 1 - NASDAQ Time Series Forecasting and Sentiment Analysis WebApp using Streamlit](https://github.com/zmalone91/Stock_Prediction)
* Interactive web app using streamlit to pull stock price data for the top 100 NASDAQ stocks from 2015 to present.<br>
* The purpose of the app is to perform a simple Time Series forecast using fbprophet on tech stocks as well as analyzing the recent trading activity and overall trend with YTD candelstick charts. <br>
* There is also an additional Sentiment Report page that utilizes the free Twitter API via Tweepy to perform an analysis on the recent tweets surrounding a specific stock. <br><br>
![Forecast_Page_1](https://user-images.githubusercontent.com/34782953/141825954-ff8c391a-063f-4c67-96e8-1991dc0dac4e.png)<br>
![Forecast_Page_2](https://user-images.githubusercontent.com/34782953/141826018-2674a5ba-995b-423a-bba1-ac7aa5992f89.png)<br>
![Sentiment_Page](https://user-images.githubusercontent.com/34782953/141826079-e901f7a7-0f59-49f2-a7bd-5c729c9bec7b.png)<br>

# [Project 2 - Cryptocurrency Comparison and Sentiment Analysis WebApp using Dash: Project Overview](https://github.com/zmalone91/Crypto_Sentiment)
* Created a web app using python dash to compare prices between two cryptocurrencies side-by-side and simultaneously search tweets about the cryptocurrencies to perform a basic negative/positive sentiment analysis.
* The purpose of the app is to assist in short-term trading strategy by getting a feel of the most recent price trends and feelings on Twitter.
* Dash web application houses the data and includes a dropdown list of all current products available on Coinbase Pro that have a USD trading pair.
* Selecting cryptocurrencies from the dropdown lists automatically updates the price chart and tweet sentiment analysis.
* The tool dynamically brings in 24 hours worth of historical data using the Coinbase Pro API python library cbpro.
* Using tweepy, tool dynamically brings in the most recent 100 tweets and who tweeted, their follower count, and the Positive/Neutral/Negative sentiment analysis of their tweet using TextBlob. <br><br>
![Crytpo screenshot](https://user-images.githubusercontent.com/34782953/140014540-3509be2b-fc76-4cb6-a38b-c79ceb5402d1.png)

# Sports-Popularity-Forecast
## Time series model for Forecasting Sports League Popularity
This project is to measure the popularity of each league using the search data collected from Google Trends, which give real-time historical data on search words. With this project, it is also possible to compare and forecast how the sports league are trending with respect to each other using five models — Holt-Winters Multiplicative (HWMM), Naive method, simple avg, Holt's Linear method and Seasonal Autoregressive Integrated Moving Average (SARIMA). Businesses interested in advertising or investing with either league may leverage these forecasts for deciding which sports league provides the greater or long-term value.
Forecasting has been a growing trend in the world of sports, where it has been used in an 
attempt to predict outcomes of games  (Spann and Skiera, 2009). Our analysis focuses on a 
separate and more general area within sports, the popularity of entire leagues. The average NFL 
team is worth $2.3 billion and the average NBA team is worth $1.25 billion (Ozanian, 2016, Baden 
hausen, 2016).  With such large market values, even small changes in future popularity could have 
large business implications on marketing, social media promotion, and team value. 
In order to model sport popularity, data is pulled from Google Trends. Google Trends is an 
analytical tool that allows users to compare the popularity of search terms over time. Google Trends can be used to gain insights into popularity that may not otherwise be noticed, as shown in the 
recent 2016 presidential election (Rogers, 2016). Data is available from 2004 to the present, and 
we choose to use the full range of data available to us. In this project, I extracted worldwide data to give more insights. 
We find out RMSE scores, compared them for each league, and discussed five different univariate models: Naive method, simple avg, Holt-Winters Exponentiation (HWE), Holt's Linear method, and Seasonal Autoregressive Integrated Moving Average (SARIMA) models to determine the popularity trends.
## The objective of this study is to compare and contrast NBA, LA LIGA,  Premier League, and NFL popularity using univariate time series forecasting models in order to efficiently predict the trending popularity for and between the leagues. We wanted to make a confident prediction about which league is growing faster. Sports have very distinct seasons, which allowed us to build a seasonality component and trend into our models.

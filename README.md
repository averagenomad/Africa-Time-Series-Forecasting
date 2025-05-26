This project was an ambitious plan of leveraging Time Series analysis through Python. I tried to incorporate the knowledge I have gain through my Time Series Econometrics course and 
execute it via a new language I began to speak, aka Python. The initial question of interest was whether it is possible to successfully predict conflict event occurrence by looking 
at the past events alone. I was interested on how depending on the data and country my modeling technique would change. Overall, this project had a rather exploratory character, 
where I wanted to investigate the data, transform it if necessary and find the best fitting model that can be potentially used for out-of- sample forecasting. Out of 4 African countries 
I have selected that are currently involved in civil conflict, I demonstrated the full Box-Jenkins approach for two of them, namely Ethiopia and Somalia. 
The results were quite interesting as the first model on Ethiopia did not perform as great for out-of-sample forecasting, while Somalia did a much better job in predicting the events.

The project mainly consisted of 2 parts: data cleaning and Box-Jenkins ARIMA approach that comprised of 3 separate parts. 
The data cleaning and EDA part included all 4 countries for the demonstration purposes, however the final product only had 2 countries that showed the entire process from the beginning 
till the end. The final best models were capable of out-of-sample forecasting which was an ambitious beginning given that we are only using past data to predict current or 
future without any additional features. This showed that despite its parsimony, simple ARIMA model is capable of strong forecasting performance.

This project can be extended in numerous ways. Given that I only did a full analysis for 2 separate countries independent of each other, I could have seen whether there exists a 
relationship between multiple different time series, hinting on the long run equilibrium relationship using the models such as Cointegration. This is an extremely interesting application, 
showing that not only past data affects the current, but other separate time series have an effect on each other. This is extremely powerful and has impactful implications. 
In addition, I could expand the given ARIMA model to ARIMAX, which adds exogenous X variables to increase the explanatory power of the models.


# CS498 Project - "Sentiment Analysis of Social Media as a predictor for Bitcoin price volatility"
This repository will be used to hold the data and Jupyter notebook file for phase 1 of the project.

Phase 1 of the project will be to conduct a data exploration of the cryptocurrency historical datasets to ascertain if a correlation can be drawn between Bitcoin price fluctuations and the other major cryptocurrencies. The comparison will be done using the top ten cryptocurrencies by market share. The part of the project will allow us to ascertain where the findings of the sentiment analysis is applicable only to Bitcoin or  can be generalized to all cryptocurrencies.

Phase 2 will be to conduct a sentiment analysis of comments extracted from reddit.com and to plot the results against the historical price fluctuations studied in Phase 1. The initial part of Phase 2 will be to use a subset of the data collected. More specifically a one month time frame in the year 2017.

Phase 3 of the project will be to expand the techniques used in Phase 2 to incorporate the use of ever larger datasets. One of the identified datasets for reddit.com comments is in excess of 300GB. It might also include using AWS to "productionize" this project in a cloud environment.

The datasets used were downloaded using the [CryptoCompare public API](https://www.cryptocompare.com/api/#introduction)
We used the following Python wrapper available on [GitHub: cryCompare](https://github.com/stefs304/cryCompare) to simplfy the API usage.

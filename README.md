# Bitcoin-price-tracker
An interactive chart of bitcoin prices over 30 days

## Introduction

An API (Application Program Interface) lets two pieces of software talk to each other. Just like a function, you don’t have to know how the API works only its inputs and outputs. An essential type of API is a REST API that allows you to access resources via the internet. 

#### *REST APIs* 

Rest APIs (Representational State Transfer) function by sending a request, the request is communicated via HTTP message. The HTTP message usually contains a JSON file. This contains instructions for what operation we would like the service or resource to perform. In a similar manner, API returns a response, via an HTTP message, this response is usually contained within a JSON.

In cryptocurrency a popular method to display the movements of the price of a currency is by using a candlestick chart. In this project I called data from the CoinGecko API using a pycoingecko wrapper as a client. The data recieved is in JSON format and expressed within python as a dictionary of nested lists.

With the data recieved, my next step was to convert it into a pandas dataframe. After some exploration and transformation, I generated an interactive plotly chart of the data. The chart is for a period covering 30 days prior to when the program is run.

NB: Github does not display charts made with Plotly. Until that's fixed you can click [here](https://nbviewer.org/github/KelvinJC/Bitcoin-price-tracker/blob/main/Bitcoin%20price%20tracker.ipynb) to see the chart.


### Tools:
* Python
* Jupyter Notebook

### Libraries:
* Pycoingecko
* Pandas
* Numpy
* Matplotlib
* Mplfinance

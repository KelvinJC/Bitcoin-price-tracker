# Bitcoin-price-tracker
Interactive chart of bitcoin prices over 30 days

## Introduction

An API (Application Program Interface) lets two pieces of software talk to each other. Just like a function, you don’t have to know how the API works only its inputs and outputs. An essential type of API is a REST API that allows you to access resources via the internet. 

#### *REST APIs* 

Rest APIs (Representational State Transfer) function by sending a request, the request is communicated via HTTP message. The HTTP message usually contains a JSON file. This contains instructions for what operation we would like the service or resource to perform. In a similar manner, API returns a response, via an HTTP message, this response is usually contained within a JSON.

In cryptocurrency a popular method to display the movements of the price of a currency is by using a candlestick chart. So we're going to call data from the CoinGecko API using a pycoingecko wrapper as a client. The data recieved is in JSON format and expressed within python as a dictionary of nested lists.



NB: Github does not display charts made with Plotly. Until that's fixed you can click [here](https://nbviewer.org/github/KelvinJC/Bitcoin-price-tracker/blob/main/Bitcoin%20price%20tracker.ipynb) to see the chart.


Tools:
Plotly
Pandas


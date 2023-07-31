# Earthquakes-Prediction-with-RNNs

# 🌎Earthquakes Prediction🌍with RNNs🌏

### Author: Victor Manuel Fonte Chavez

## Problem Description:

In this project, data was taken from earthquake readings around the world during the month of April 2023 to predict the location and magnitude of the next 10 earthquakes. It should be noted that these data are not regularly spaced in time, so interpolation will be required to obtain a well-defined time series. However, this step will be skipped this time because the data is very spread out over short periods of time, making it difficult to get accurate data over a certain distance without adding too much bias to the data.

Consequently, it has been decided to approach the problem in the following way: obtain a model that allows to approximately predict the latitude and longitude of the next earthquake with a scale greater than 4.5 in the world. For this, the data of the earthquakes of the same magnitude that occurred in the month of April will be taken into account, in addition to the estimated magnitude of the earthquake to be predicted.

## Methodology

It will begin with a descriptive analysis of the data to better understand its characteristics and detect possible patterns or trends. Then, we will move on to the construction of recurrent neural network models that allow us to predict the latitude and longitude of the next earthquake of magnitude greater than 4.5 in the world.

First, a model will be built based on LSTM (Long Term Memory Neural Networks), a neural network architecture that allows learning patterns of data sequences and remembering relevant information in the long term. Then, another model that uses Vanilla RNN (Standard Recurrent Neural Networks) layers will be experimented to compare its performance with the LSTM model.

Subsequently, we will continue with a model that uses GRU layers (Gated Recurrent Units), a variant of recurrent neural networks that focuses on handling relevant information and discarding redundant information.

Finally, bidirectional layers will be added to the LSTM architecture, allowing the neural network to take into account both the past and the future of the data stream to make a more accurate prediction.

With this methodology, different recurrent neural network architectures will be compared and find the one that best fits your data to make accurate predictions of the next earthquakes of magnitude greater than 4.5.

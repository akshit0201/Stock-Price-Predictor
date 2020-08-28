# Stock-Price-Predictor
Tensorflow and LSTM based stock price predictor.<br />
Long short-term memory (LSTM) is an artificial recurrent neural network (RNN) architecture used in the field of deep learning. Unlike standard feed forward neural networks, LSTM has feedback connections. It can not only process single data points (such as images), but also entire sequences of data (such as speech or video).It is used to here to remember the previous prices of the stocks , and give more recent prices more weight.
![alt text](https://iq.opengenus.org/content/images/2018/11/rnn.png)

The given code makes use of two layers of LSTM and three layers of dense neural networks to predict the price of stock based on it's movements over the past two months.
<br /> Practically any stock which is listed on Yahoo finance can have it's price predicted.Only, the name of the stock has to be changed in the dataframe reader.


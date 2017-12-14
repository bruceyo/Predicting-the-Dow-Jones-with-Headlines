# Predicting-the-Dow-Jones-with-Headlines

The goal of this project is to use the top, daily news headlines from Reddit to predict the movement of the Dow Jones Industrial Average. The data for this project spans from 2008-08-08 to 2016-07-01, and is from this [Kaggle dataset](https://www.kaggle.com/aaron7sun/stocknews). 

The news from a given day will be used to predict the difference in close price between that day, and the following day. This method is chosen because it should allow all of the day's news to be incorporated into the price compared to closing price.

For this project, we will use GloVe to create our word embeddings and CNNs followed by LSTMs to build our model. This model is based off the work done in this paper https://www.aclweb.org/anthology/C/C16/C16-1229.pdf.

--

Running Environment:
OS: Ubuntu 16.04 LTS

Python: version 2.7

Tensorflow: with GPU version 1.0.1

Keras: 2.1.0


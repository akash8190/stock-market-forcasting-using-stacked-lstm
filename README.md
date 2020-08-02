# stock-market-forcasting-using-stacked-lstm

![alt text](https://cdn-images-1.medium.com/max/2000/1*1tDxGyGI4hnUf50a4LX5hQ.png)


## project overview

In this project we simply forcast the stock price of apple with the help of deep learning algoritham name stacked lstm.we simply try to predict future stock for 10 days

## deep learning

![alt text](https://orbograph.com/wp-content/uploads/2019/01/DeepLearn.png)



Deep learning is an AI function that mimics the workings of the human brain in processing data for use in detecting objects, recognizing speech, translating languages, and making decisions. Deep learning AI is able to learn without human supervision, drawing from data that is both unstructured and unlabeled.

##  lstm

![alt text](https://upload.wikimedia.org/wikipedia/commons/3/3b/The_LSTM_cell.png)


Long Short Term Memory networks – usually just called “LSTMs” – are a special kind of RNN, capable of learning long-term dependencies. They were introduced by Hochreiter & Schmidhuber (1997), and were refined and popularized by many people in following work.1 They work tremendously well on a large variety of problems, and are now widely used.

LSTMs are explicitly designed to avoid the long-term dependency problem. Remembering information for long periods of time is practically their default behavior, not something they struggle to learn!

All recurrent neural networks have the form of a chain of repeating modules of neural network. In standard RNNs, this repeating module will have a very simple structure, such as a single tanh layer


##  About time series data

![alt text](https://3qeqpr26caki16dnhd19sv6by6v-wpengine.netdna-ssl.com/wp-content/uploads/2017/03/Line-Plot-of-Shampoo-Sales-Dataset-with-Multi-Step-LSTM-Forecasts.png)



Time series forecasting refers to the type of problems where we have to predict an outcome based on time dependent inputs. A typical example of time series data is stock market data where stock prices change with time. Similarly, the hourly temperature of a particular place also changes and can also be considered as time series data. Time series data is basically a sequence of data, hence time series problems are often referred to as sequence problems.


## data collection
 
 In thi forcasting project we simply collect data from third part api using panda_datareader link of third party api https://www.tiingo.com/ where you can collect 5 year data from any company like google apple samsung any listed or big company and simply analyze those data,and you can also create your own api key from register from that website,and use api key on you code so that it can extract data from that website

## Technolgy used

 python keras tensorflow google colab
 
 ## blog you refer
 
 link of blog https://stackabuse.com/solving-sequence-problems-with-lstm-in-keras/







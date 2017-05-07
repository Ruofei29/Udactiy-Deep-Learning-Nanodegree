# P1 First Neural Network

## Project Overview
I built my first neural network and used it to predict daily bike rental ridership.

## Reflection
My thoughts:
* At first, I really struggle with the dimension of array. Then I learned a lot of linear algreba to help me with it.
* When the epochs increase, it will denefitely increase the training time and also increase the train loss which make it as close as to validation loss. I don't want to put a very large number since it will cost crazy time to train.
* When I decrease the learning rate below 0.02, the training loss and validation weren't improved much. So I keep 0.02.
* When I increase the hidden nodes from 1 to 30, I do see a significant drop for both training and validation loss. I choose 22 for the time efficience and the loss is pretty stable from 22-30.

Moving forward: The first thing I can do is to change different activation function and find the most appropriate one. Also, this time we put the most simple activation function to our final output, we can change that, too. Also, getting more data will help our network to learn more and make more accurate prediction.

## Report
Please see [dlnd-your-first-neural-network.ipynb](https://github.com/Ruofei29/Udactiy-Deep-Learning-Nanodegree/blob/master/P1%20First%20Neural%20Network/dlnd-your-first-neural-network.ipynb)

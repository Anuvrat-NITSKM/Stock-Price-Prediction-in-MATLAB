# Stock-Price-Prediction-in-MATLAB
Predicting how the stock market will perform is difficult as there are so many factors involved  which combine to make share prices volatile and very difficult to predict with a high degree of accuracy. We use machine learning as a game changer in this domain. Using features like latest announcements about an organization, their quarterly revenue results, etc., machine learning techniques have the potential to unearth patterns and insights to make unerringly accurate predictions.
## Convolutional neural network (CNN or ConvNet):
It is a network architecture for deep learning which learns directly from data, eliminating the need for manual feature extraction.Using CNNs for deep learning is popular due to three important factors:<br />
CNNs eliminate the need for manual feature extraction—the features are learned directly by the CNN.<br />
CNNs produce highly accurate recognition results.<br />
CNNs can be retrained for new recognition tasks, enabling you to build on pre-existing networks.<br />
Three of the most common layers are: convolution, activation or ReLU, and pooling.<br />
Convolution puts the input through a set of convolutional filters, each of which activates certain features.<br />
Rectified linear unit (ReLU) allows for faster and more effective training by mapping negative values to zero and maintaining positive values. This is sometimes referred to as activation, because only the activated features are carried forward into the next layer.<br />
Pooling simplifies the output by performing nonlinear downsampling, reducing the number of parameters that the network needs to learn.These operations are repeated over tens or hundreds of layers, with each layer learning to identify different features.<br />

## Problem Statement
There are many datasets available for the stock market prices.This project aims to predict the future price of the stock market based on the previous year’s data using Convolutional Neural Networks.<br />
## Graph for actual and predicted stock prices:
![image](https://user-images.githubusercontent.com/58883201/119706688-ece8d680-be77-11eb-8c4b-6d1d15df7d18.png)<br />
## Training the Neural Network:
![image](https://user-images.githubusercontent.com/58883201/119706725-f5d9a800-be77-11eb-9a5e-9f0fadaa05a0.png)<br />
## Gradient, Validation Check, Learning Rate:
![image](https://user-images.githubusercontent.com/58883201/119706749-feca7980-be77-11eb-9dca-148a9a996feb.png)<br />
## Best Training Performance:
![image](https://user-images.githubusercontent.com/58883201/119706779-08ec7800-be78-11eb-85b5-966ebcfcbd2b.png)<br />
## Neural Network Training Regression(plot regression), Epoch 8000(max epoch reached):
![image](https://user-images.githubusercontent.com/58883201/119706830-143fa380-be78-11eb-98c1-359bd02489df.png)<br />
## Conclusion 
The Convolutional Neural Network accurately predicted the stock prices based on the training set provided.<br />
The best training performance is 7.9171 at epoch 7999 out of the 8000 epoches.<br />
Network Training Regression is 0.99794( close to 1).<br />



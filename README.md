# Make_a_neural_network
This is the code for the "Make a Neural Network" - Intro to Deep Learning #2 by Siraj Raval on Youtube

##Overview

This is the code for [this](https://youtu.be/p69khggr1Jo) video by Siraj Raval on Youtube. This is a [simple](http://computing.dcu.ie/~humphrys/Notes/Neural/single.neural.html) single layer feedforward neural network (perceptron). We use binary digits as our inputs and expect binary digits as our outputs. We'll use [backpropagation](http://neuralnetworksanddeeplearning.com/chap2.html) via gradient descent to train our network and make our prediction as accurate as possible.

##Dependencies

None! Just numpy.

##Usage

Run ``python demo.py`` in terminal to see it train, then predict.

##Challenge

The challenge for this video is to create a 3 layer feedforward neural network using only numpy as your dependency. By doing this, you'll understand exactly how backpropagation works and develop an intuitive understanding of neural networks, which will be useful for more the more complex nets we build in the future. Backpropagation usually involves recursively taking derivatives, but in our 1 layer demo there was no recursion so was a trivial case of backpropagation. In this challenge, there will be. Use a small binary dataset, you can define one programmatically like in this example.

**Bonus -- use a larger, more interesting dataset**

##Credits

The credits for this code go to [Milo Harper](https://github.com/miloharper). I've merely created a wrapper to get people started.



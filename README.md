# Neural Network
My attempt at making a neural network. Currently it's just a template made to be built off of

## Usage
when you want to import the network, use this python code:
```
import neural

learning_rate=0.1 #A good default, seems to prevent overfitting
neural_network=neural.NeuralNetwork(learning_rate)
```
Currently, the network is very simple, only trying to find a target that's either one or zero

## How it works
Currently very simple. Only contains two layers. The first layer computes the dot product of the vectors with the bias. The second layer transforms the data with the sigmoid function
$$S(x)=1/1+e^x$$

# Neural-Networks

A neural network is a series of algorithms that endeavors to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates. In this sense, neural networks refer to systems of neurons, either organic or artificial in nature.

Neural networks can adapt to changing input; so the network generates the best possible result without needing to redesign the output criteria. The concept of neural networks, which has its roots in artificial intelligence, is swiftly gaining popularity in the development of trading systems.

(From investopedia: https://www.investopedia.com/terms/n/neuralnetwork.asp#:~:text=A%20neural%20network%20is%20a,organic%20or%20artificial%20in%20nature.)

## Perceptron

This is an algorithm for supervised learning of binary classifiers. A binary classifier is a function which can decide whether or not an input, represented by a vector of numbers, belongs to some specific class. It is a type of linear classifier, i.e. a classification algorithm that makes its predictions based on a linear predictor function combining a set of weights with the feature vector.

(From Wikipedia, the free encyclopedia: https://en.wikipedia.org/wiki/Perceptron.)

### Process
Generatation of 8 random inputs, with 2 pre-assigned classes (0-1). The TLU is plotted:

![image](https://user-images.githubusercontent.com/86708470/167499197-d68ce99c-1649-4ff0-b7b2-91dd661a7f70.png)


## Multilayer Perceptron (MLP)
A multilayer perceptron (MLP) is a fully connected class of feedforward artificial neural network (ANN). 
Consists of at least three layers of nodes: an input layer, a hidden layer and an output layer. Except for the input nodes, each node is a neuron that uses a nonlinear activation function. MLP utilizes a supervised learning technique called backpropagation for training. Its multiple layers and non-linear activation distinguish MLP from a linear perceptron. It can distinguish data that is not linearly separable.

(From Wikipedia, the free encyclopedia: https://en.wikipedia.org/wiki/Multilayer_perceptron)

The data set is called "TripGaussKNN.csv".

### Data Generation.
Generatation of 3,000 random values, 3 clases (0,1,2).

![image](https://user-images.githubusercontent.com/86708470/167902422-42453999-7b54-4526-bcee-6c8f9b1954d9.png)

### Results

Accuracy of: 0.96466%

![image](https://user-images.githubusercontent.com/86708470/167902561-e9713f17-fa5a-4eb8-b59a-e84e3c0a262e.png)


## N-Layer Perceptron
An implementation of the program "Multilayer Perceptron (MLP)", Backpropagation, short for "backward propagation of errors," is an algorithm for supervised learning of artificial neural networks using gradient descent. Given an artificial neural network and an error function, the method calculates the gradient of the error function with respect to the neural network's weights.

(From Brilliant, John McGonagle, George Shaikouski, Christopher Williams, and 3 others contributed: https://brilliant.org/wiki/backpropagation/#:~:text=Backpropagation%2C%20short%20for%20%22backward%20propagation,to%20the%20neural%20network's%20weights.)

The data set is called "TripGaussKNN.csv".

### Results

Accuracy of: 0.9707%

![image](https://user-images.githubusercontent.com/86708470/167921235-a13eee52-477b-4fbf-b05e-817f5aba2a03.png)

### Prediction Technique

Accuracy of: 0.9866%

![image](https://user-images.githubusercontent.com/86708470/167921378-0fba207a-276b-457e-a748-c3afac949327.png)

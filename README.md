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
Distance computation in k-Means weighs each dimension equally and hence care must be taken to ensure that unit of dimension shouldn’t distort relative near-ness of observations. Common method is to unit-standardize each dimension individually.

![image](https://user-images.githubusercontent.com/86708470/167463458-20f8c7ad-f307-49ff-8c7f-8e1476f53fec.png)

### Results

Final k-means clustering pipeline was able to cluster tweets with different classes.

![image](https://user-images.githubusercontent.com/86708470/167464243-34d11c96-c41e-44cf-b29d-8948a75da0c6.png)

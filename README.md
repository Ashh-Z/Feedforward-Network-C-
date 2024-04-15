# Implementation of a Neural Network from Scratch in C++

> Only using the C++ STL (standard template library).

## Compilation & Usage

You can either import the code in an empty console project in VisualStudio or compile it directly on the command line with:

```
g++ -Wall -Wpedantic main.cpp NeuralNetwork.cpp
```
Simply running it will read the provided `csv` file from the same directory, train the network and attempt predictions afterwards. Based on the results of the predictions the accuracy is calculated and subsequently printed to `stdout`.

### Result

Using this network on the given seed dataset (and cross-validation) we are able to achieve an approximate accuracy of more than 90%.

The following result was achieved using a learning rate of 0.3 with 500 epochs and 5 neurons in the first hidden layer on a network with one hidden and one output layer.

![Screenshot of example output](ExampleOutput.PNG)

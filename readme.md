# A generalized approach to neural networks
This library is intended to be a generalized model of neural networks, which enable computer to learn. The idea is to combine existing NN-ideas and combine them into one project, so you not only have to have different libraries, but you can also combine the different algorithms.

# Why JavaScript?
I decided to write this library in JavaScript because it basically runs on every Internet-enabled device, enabling it to run on the most kinds of devices. Another factor was that it can be either run on the web, which means there is no setup required to execute it, or on the desktop with the help of NodeJS. In addition JavaScript is one of the easiest to learn languages.

# Features
- A generalized BPTT (back-propagation through time)
- Abstract layer-network model
- Network and data are seperated

# Current layer implementations
- Fully connected layer (Dot)
- Convolutional layer
- Long Short-Term memory layers
- Softmax and hierarchical softmax layer
- Non-linear layers like sigmoid, tanh and rectifier
- Regression and input layer
- Drop-out layer

# Acknowledgments
I would like to thank @karpathy (Andrej Karpathy) for his rigorous work on JavaScript deep-learning libraries, which I took inspiration and help from. (In parts you can see that in the code)

# License
MIT
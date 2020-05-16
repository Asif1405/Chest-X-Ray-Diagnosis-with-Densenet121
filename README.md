# Chest-X-Ray-Diagnosis-with-Densenet121

### Overview:
In this project I used a DenseNet to create a medical imaging of chest x-rays to detect primarily pneumonia among other chest diseases. 

Dense Convolutional Network (DenseNet) is a convolutional neural network which connects each layer to every other layer in a feed-forward fashion. Whereas traditional convolutional networks with L layers have L connections — one between each layer and its subsequent layer — our network has L(L+1)/ 2 direct connections. For each layer, the feature-maps of all preceding layers are used as inputs, and its own feature-maps are used as inputs into all subsequent layers. DenseNets have several compelling advantages: they alleviate the vanishing-gradient problem, strengthen feature propagation, encourage feature reuse, and substantially reduce the number of parameters.

### Requirements:
Python 3.x

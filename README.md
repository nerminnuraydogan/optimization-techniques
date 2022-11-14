# Optimization Techniques used in Neural Networks

Implementations and discussions on the following topics: 

>### Batch Normalization

Batch normalization is introduced in the paper [Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/pdf/1502.03167.pdf). In the notebook provided, the mathematical representation, and benefits of batch normalization are discussed and a simple implementation with NumPy is provided. Additionally, models with batch normalization applied and excluded are experimented on to test whether batch normalization has the benefits discussed with PyTorch. 

>### Gradient Descent

Backpropagation is an important concept in Neural Networks. To optimize weights in a neural network, we need to perform backpropagation. In order to understand how neural networks work, we need to understand how backpropagation works under the hood. **The essential components of backpropagation can be explained with two primary concepts: chain rule and derivative.** In the provided notebook, these concepts are discussed to explain backpropagation. Primarily, we can chain the derivatives of the applied functions recursively to obtain the backward pass. A simple NumPy implementation is included with linear data.

>### Weight Initialization

Weight initialization is an important pre-step to training neural networks. A poorly initialized weight can lead to a neural network model not converging properly. There are plenty of methods that are applied to effectively use the weights of a network. In the provided notebook, weight initialization with normal distribution and a uniform distribution has experimented with PyTorch.

The above content is an expanded version of the exercises from the Udacity Deep Learning Course notebooks.

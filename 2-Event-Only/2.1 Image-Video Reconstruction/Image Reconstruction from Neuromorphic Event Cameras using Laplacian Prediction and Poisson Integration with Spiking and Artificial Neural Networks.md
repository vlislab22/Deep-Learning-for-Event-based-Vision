# Image Reconstruction from Neuromorphic Event Cameras using Laplacian Prediction and Poisson Integration with Spiking and Artificial Neural Networks

CVPRW 2021

# Research Question

How to achieve adequate image reconstruction with less parameters?

# Motivation

1) The Neural Engineering Framework (NEF) is one of the most utilized theoretical frameworks in neuromorphic computing. It brings forth a theoretical framework for a neuromorphic encoding, decoding, and transformation of mathematical constructs with spiking neurons, allowing the 
implementation of functional large-scale neural networks.

2) Previous method utilizes Laplacian Prediction and Poisson Integration to reconstruct the intensity images, which could provide some sights.

# Contribution

1) They propose an even more compact non-spiking CNN, with Mish activation, achieving adequate image reconstruction with less than 100 parameters.

2) They combine the optimization method and deep learning method.

# Method

1) They initiates with a CNN, which predicts the 
Image’s Laplacian given frame tensors, followed by a SNN optimized for Poisson Integration.

2) They propose a five-layer CNN, where the first two comprise single strided
3x3 convolutions (without down-sampling), and the last three layers comprise a single-strided 1x1 convolution kernel. 

3) The trained CNN was converted to SNN using the Neural Engineering Framework (NEF)-based NengoDL library. ReLU activations were converted to Spiking rectified linear activation in the SNN.

4) To neuromorphically implement Poisson integration, we designed a feedforward SNN. By using a finite difference numerical method, the Poisson equation can be rewritten as a linear system $AU=B$. The size of A depends on the image dimension. They assume a fixed $W$ matrix, where $W=A^{-1}$. The 
reconstructed image vector $U$ can be calculated using $U=WB$

# Weakness

1) They assume a fixed $W$ matrix, which is a strong assumption. This cause the sub-optimal performance of the model.

2) Although their method have few parameters, they could not perform well in the image reconstruction task.
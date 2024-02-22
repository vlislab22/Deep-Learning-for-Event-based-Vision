# Event-based Asynchronous Sparse Convolutional Networks

ECCV 2020

## Research Question:
	How to efficiently extract information from a stream of events?

## Motivation:
Methods that utilize synchronous dense, image-like representation discard the spatial and temporal sparsity inherent in event data at the cost of higher computational complexity and latency.


## Contribution:
A general framework for converting models trained on synchronous image-like event representations into asynchronous models with identical output.
 

## Highlight:
(1) The converted asynchronous model match the performance of high capacity neural networks but with up 20 times less computation.  

(2) It is agnostic to the event representation, neural network architecture, and task. Also it not require any change in the optimization or training process.   

(3) It fully exploits the spatio-temporal sparsity of the event data.

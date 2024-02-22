# End-to-End Learning of Representations for Asynchronous Event-Based Data

ICCV 2019 

## Research Question:
	How best to transform an asynchronous event stream to a image-like/tensor representation, and keep high performance in a specific downstream task meantime?
	
## Motivation:
(1) Converting asynchronous event data to tensor-like representation for the adaptation of process of CNN-based model.  
(2) Existing methods are fixed and suboptimal for tensor-like transformation, not learnable and end-to-end.    


## Contribution:
A general framework to convert event streams into grid-based representations, i.e., Event Spike Tensor(EST), through a sequence of differentiable operations(MLP).
 

## Highlight:
(1) It's available to learn event representation together with task-specific network in an end-to-end manner.    

(2) The formulaic unification of several existing event representation.  

(3) EST remains the maximum amount of event information by four-dimensional data structure (two spatial, one temporal, and one polarity).

## Weakness:
This method ignors the sparse and asynchronous property of event data, and abtains high performance at the cost of redunant computation, high latency and bandwidth.

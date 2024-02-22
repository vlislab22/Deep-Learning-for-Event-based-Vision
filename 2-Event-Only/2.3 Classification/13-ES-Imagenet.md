# AEGNN: Asynchronous Event-based Graph Neural Networks

CVPR 2022

## Research Question:
    How to efficiently deal with event data, meanwhile taking into account sparsity and asynchronization using GNN?
    
## Motivation:
(1) Existing tensor-like representation based methods are computationally heavy and with high latency as ignoring sparsity and high temporal resolution of events.

(2) Events only measure single pixel changes and, thus, leave most of the activations unchanged, leading to unnecessary recomputation of activations.

## Contribution:
(1) AEGNN, an efficient framework for processing events sparsely and asynchronously as temporally evolving graphs.

## Highlight
(1) For each new event, only perform local changes to the activations of the GNN, and propagate these asynchronously to lower layers.

(2) AEGNN can be trained on synchronous event data and deployed on asynchronous data during the test.
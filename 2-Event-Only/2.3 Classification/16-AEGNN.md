# AEGNN: Asynchronous Event-based Graph Neural Networks

CVPR 2022

## Research Question:
	How to efficiently, sparsely, and asynchronously deal with event data by GCN? 

## Motivation:
(1) Dense representation based methods discard both the sparsity and high temporal resolution of events, leading to high computational burden and latency.

(2) Events only measure single pixel changes and, thus, leave most of the activations unchanged, leading to unnecessary recomputation of activations.

## Contribution:
(1) AEGNN, a novel paradigm for processing events sparsely and asynchronously as temporally evolving graphs.

(2) Efficient update rules, which allow the model trained on synchronous event-data, and deployed as an asynchronous mode during test time.

## Highlight:
(1) For each new event, AEGNN only performs local changes to the activations of the GNN, and propagates these asynchronously to lower layers.

(2) With 200 times lower computational complexity than state-of-the-art asynchronous method, while achieving state-of-the-art results.

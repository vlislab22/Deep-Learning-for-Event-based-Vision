# Graph-based Asynchronous Event Processing for Rapid Object Recognition

ICCV 2021

## Research Question:
	How to reduce both computation and latency for event-by-event processing? 

## Motivation:
(1) Although event-by-event methods (Time- surface-based methods and SNNs) keep low latency, suffer from limited accuracy in high-level tasks.

(2) Compact graph representation at the cost of discarding the low latency nature of events data.

(2) Previous works lack the ability of early recognition.

## Contribution:
(1) Graph-based recursive algorithm with a sliding window strategy that can process the stream event-by-event efficiently while maintaining high accuracy.

(2) Novel incremental graph convolution (slide convolution) for event-wise processing.

(3) Event-specific radius search algorithm that reduces query and insertion/deletion costs to make graph construction faster.

## Highlight:
(1) The first ones to verify the superiority of event-wise processing in early object recognition.

(2) Reducing the computational complexity up to 100 times by specific propagation rules in comparison with the naive sliding window strategy.

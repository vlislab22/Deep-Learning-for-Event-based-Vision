# Fast Event-based Corner Detection

BMVC 2017

## Research Question:
	How to reduce the massive parallel computation during event-based data processing?

## Motivation:
(1) Corners are useful features as they are well localized, highly informative, and do not suffer from the aperture problem.  
(2) Frame-based pre-processing techniques that reduce an image to a set of features, which are typically the input to higher-level algorithms.


## Contribution:
(1) A fast method for corner detection in an event stream(reduce an event stream to a corner event stream).

(2) A lightweight, low-latency preprocessing step for subsequent higher-level algorithms.


## Highlight:
(1) It's efficient as working on the Surface of Active Events using only comparison operations.  

(2) This method asynchronously processes event by event with very low latency, thus preserving the characteristics of the event stream.

(3) It can process more than a million events per second on a single core, and typically reduces the event rate by a factor of 10 to 20.

## Weakness:
Corner detection quality is worse than existing method.

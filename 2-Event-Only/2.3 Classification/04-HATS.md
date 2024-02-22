# HATS: Histograms of Averaged Time Surfaces for Robust Event-based Object Classification

CVPR 2018

## Research Question:
	How to build a robust representation for event-based object classification?
	
## Motivation:
(1) The research on low-level representation and architecture for event-based object classification is limited.  
(2) The lack of a large real-world event-based dataset.


## Contribution:
(1) A scalable machine learning architecture for histogram computing.

(2) Histograms of Averaged Time Surfaces(HATS), a novel event-based feature representation.

(3) N-CARS, the first large real-world event-based dataset for object classification.
 

## Highlight:
(1) Time surface provides spatio-temporal information by encoding dynamic context from neighboring pixels of events.  

(2) Memory units are used to store historical events in case forgetting of the algorithm.  

## Weakness:
The HATS representation is not validated in other tasks besides classification.  
# A Voxel Graph CNN for Object Classification with Event Cameras

CVPR 2022

## Research Question:
    How to balance accuracy and model complexity for event-based classification models?
    
## Motivation:
(1) Is point-wise input (taking event points as processing units) proper for event-based vision tasks?

(2) Event-based classification models require the ability to accurately extract 2D semantics from the event data rather than their “geometry”, which usually contains motion cues or motion trajectories.

## Contribution:
(1) A novel graph representation for event data to exploit their sparsity better.

(2) A lightweight voxel graph convolutional neural network (EV-VGCNN) for event-based classification.

## Highlight:
(1) Using voxel-wise vertices rather than previous point-wise inputs to explicitly exploit regional 2D semantics of event streams while keeping the sparsity.

(2) Multi-scale feature relational layer (MFRL) to extract semantic and motion cues from each vertex discriminatively.

## Weakness:
(1) The method is based on the assumption that the input event data to the model always relate to objects.

(2) Synchronous processing pattern sacrifice real-time performance.
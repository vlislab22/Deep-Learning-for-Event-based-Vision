# A Differentiable Recurrent Surface for Asynchronous Event-Based Data

ECCV 2020

## Research Question:
    How to effectively aggregate event information in grid-based representations? 


## Motivation:
(1) The great success of frame-based deep learning architectures.

(2) Existing hand-crafted grids that reconstruct the frame using ad-hoc heuristics.

## Contribution:
(1) Matrix-LSTM, a task-independent mechanism to extract grid-like event representations.

(2) It can consistently boost the performance of optical flow estimation and object classification.  

## Highlight:
(1) The mechanism is end-to-end differentiable and it can be used as input for any existing frame-based CNN model.

(2) It can adaptatively integrate and utilize information of events by the memory mechanism of LSTM.

## Weakness:
Matrix-LSTM is performing slower than EST. 


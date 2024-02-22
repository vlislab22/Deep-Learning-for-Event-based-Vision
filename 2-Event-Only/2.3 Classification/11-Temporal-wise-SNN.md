# Temporal-wise Attention Spiking Neural Networks for Event Streams Classification

ICCV 2021

## Research Question:
    How to effectively and efficiently extract frame-based event representation with SNN?   

## Motivation:
(1) As a brain-inspired event-triggered computing model, SNN can extract effective spatio-temporal features from the event streams.

(2) The signal-to-noise ratios of aggregated event frames are different, thus diverse importance should be attached.

## Contribution:
(1) A temporal-wise attention SNN(TA-SNN) model to learn frame-based representation.

(2) Input attention pruning(IAP) mechanism that keep the event-encoded data characteristics.

(3) Random consecutive slice(RCS) module to conduct data augmentation.

## Highlight:
(1) Using temporal-wise attention to judge the significance of frames for the final decision at the training stage, and discard the irrelevant frames at the inference stage.

(2) The first work to introduce temporal-wise attention into SNNs. 

(3) IAP module bring similar or even better performance compared with those using full inputs.
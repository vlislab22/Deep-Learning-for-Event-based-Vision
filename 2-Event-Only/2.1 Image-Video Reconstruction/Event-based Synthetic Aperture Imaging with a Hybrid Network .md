# Event-based Synthetic Aperture Imaging with a Hybrid Network

CVPR 2021

# Research Question

1) Conventional frame-based cameras introduce disturbance to the **Synthetic aperture imaging** when it comes to the very dense occlusions
and extreme lighting conditions.
2) How to effectively process the event stream and reconstruct the high quality visual images of occluded targets?

# Motivation

1) For the spiking neural network, the spatiotemporal information is naturally encoded in the spike position and timing.
2) CNN is able to decode the rich output of SNN, and effectively reconstruct the visual image of occluded targets.

# Contribution

1) They present a novel event-based SAI algorithm with systematic analysis, which can overcome the dilemma that the conventional F-SAI faces under very dense occlusions
and extreme lighting conditions.
2) They propose a hybrid SNN-CNN encoder-decoder network to reconstruct high quality visual images.
3) They build an event-based Synthetic aperture imaging dataset 

# Method

1) Event Refocusing by utilizing multi-view geometry and pinhole imaging model.
2) Reconstruct the image by combining a Hybrid Network(SNN+CNN). 

# Weakness

1) They don't propose new structure,just combine the existing model.
2) They assume that the event camera keeps staying on the camera plane and the optical axes of all camera poses are parallel. This is not always the real case.
3) Experiment is not enough.

# Why it could accepted by CVPR

1) They explore a new setting: Event cameras for SAI.
2) They combine the SNN and CNN to generate high quality image.
3) They construct a new dataset.
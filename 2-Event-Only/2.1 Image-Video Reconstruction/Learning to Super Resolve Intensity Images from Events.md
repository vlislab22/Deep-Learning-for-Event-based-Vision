# Learning to Super Resolve Intensity Images from Events

CVPR 2021

# Research Question

As most commercially available event cameras produce relatively low resolution event streams for  their efficiency. While there are number of proposals on
many applications estimating super-resolved intensity images from the events has been barely explored in the literature. Previous approaches are
sub-optimal in generating the high resolution images from the events and may fail to reconstruct details of scenes. 
They raise a research question: **How to produce high fidelity high resolution images and estimate pixel-wise super-resolved intensity
from events in an end-to-end manner?** 

# Main Contributions

1) They propose the first end-to-end learning framework to model super-resolving event data to higher-resolution intensity images.
2) They further extend the method to reconstruct more details by considering active sensor pixel frames as inputs or learning the network iteratively to add details to an initial image.
3) They utilize the internal memory state of recurrent neural network to reconstruct different regions with rich details in a continuous manner as the state is updated internally by each incoming stack

# Motivation

1) The stream-like representation of events is sparse in spatial domain and needs preparation to capture scene details to be reconstructed by a convolutional neural network.
2) An unwanted downside of stacking the event stream is losing temporal relation between the stacks. The lost temporal relation between stacks can be partially recovered by using
a sequence of the stacks and the optical flow between each pair of stacks as the optical flow reports how the triggered events in the scene have moved and in which location the changes have happened.

# Weaknesses

1) The proposed Similarity Loss make less sense for the performance of the model.
2) The three streams in the proposed framework just connect with the near streams.
3) The method needs to use the APS to supervise the framework.
# EventGAN: Leveraging Large Scale Image Datasets for Event Cameras

Source: ICCP 2021

# Research Question

1) Previous networks for events are limited by the amount of labeled training data available, due to the camera’s relative infancy and the cost of acquiring accurate ground truth labels. 

2) How to find an alternative to costly data labelling, by leveraging the large set of labeled image datasets via image to event simulation? 

3) How to model event noise, both in terms of erroneous events and noise in the event measurements?

# Motivation

1) Conventional simulators often cannot perfectly model the data distribution in the real world, resulting in many methods attempting to bridge this gap.

2) GANs consists of a generator trained to model the data distribution of the training set, while a discriminator is trained to differentiate between outputs from the fake and real data.

3) Optical ﬂow estimation and image reconstruction from real events may provide cues to encode this motion and intensity information.

# Contribution

1) They propose a novel network using an adversarial loss and cycle consistency losses which constrain the generator network to generate events from which pre-trained networks are able to extract accurate optical ﬂow and image reconstructions.

2) They presnt a novel pipeline for supervised training of deep neural networks for events, by simulating events from existing large scale image datasets and training on the simulated events and image labels.

# Weakness

1) The framework is difﬁcult to train.

2) The do not explain the way to produce the real noise of event data.

3) The model is complicate. It needs several pre-training stage. 

4) The wrong prediction of optic flow may worse the performance of the model.

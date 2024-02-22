# Back to Event Basics: Self-Supervised Learning of Image Reconstruction for Event Cameras via Photometric Constancy

Source: ICCP 2021

# Research Question

1) How to reduce the simulator-to-reality gap?

# Motivation

1) Optical Flow via Contrast Maximization.

2) Reconstruction via Photometric Constancy.

# Contribution

1) They propose a novel SSL framework to train artificial neural networks
to perform event-based image reconstruction that, with the aid of optical flow, does not require ground truth of any kind and can learn directly on real event data.

2) They present a novel, lightweight neural network architecture that performs fast optical ﬂow estimation from events.

# Method

1) They use the contrast maximization proxy loss for motion compensation and
optic flow estimation.

2) They formulate the SSL reconstruction problem from an image registration perspective via brightness increment
images. Specfically, we propose to use the difference between
the reference increment image event integration and the predicted photometric constancy to reconstruct the brightness signal that best explains the input events, assuming known error-free optical ﬂow. 

# Weakness

1) The framework is difficult to train.

2) The method can not be applied to fast-motion setting.
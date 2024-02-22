# Reducing the Sim-to-Real Gap for Event Cameras

ECCV 2020

# Research Question

How to reduce the mismatch between synthetic and real data degrades performance and simulate realistic data?

# Main Contributions

1) They propose to generate synthetic training data that improves generalizability to real event data, guided by statistical analysis of existing
datasets (keep the same contrast threshold).
2) They propose a dynamic train-time event noise augmentation method.
3) They provide a new comprehensive High Quality Frames dataset targeting ground truth image frames for video reconstruction evaluation.

# Motivation

1) They find that the contrast threshold (CT) - the minimum change in brightness required to trigger an event - is a key simulation parameter
that impacts performance of supervised CNNs. 
2) Further, they observe that the apparent contrast threshold of real event cameras varies greatly, even within one dataset.

# Weaknesses

1) It is time-consuming for application because the method need the training data to generate synthetic data.
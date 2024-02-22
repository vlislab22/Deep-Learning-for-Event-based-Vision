# Event-Based High Frame-Rate  Video Reconstruction With A Novel Cycle-Event  Network

Source: ICIP 2020

# Research Question

How to reconstruct an image with less noise background and more textural details with unpaired data for training?

# Motivation

1) Previous methods require paired training data, e.g. events and its corresponding intensity image (ground truth), which is not an easy task since the imbalance of events with extremely high temporal rate and intensity frame with relatively low frame-rate.

2) The ground truth intensity image often with blurs especially when cameras and scenes have relative motions. 

3) The reconstruction of high frame-rate video from events is an ill-posed problem, because events are commonly contaminated by noises and only convey edge information leading to insufﬁcient texture details.

# Contribution

1) They firstly propose a Cycle-Event Network, which does not need paired image for training.

2) They propose a novel Residual Channel-wise Attention
Gate to guide the multi-scale feature fusion, suppress the complex background disturbance, and retain richer textural details.

# Weakness

1) The way they don't use the paired data is to mess up the paired data, which makes nonsense.

2) The proposed Residual Channel-wise Attention
Gate is not creativity.

3) Their experiment (only one experiment) is not enough.
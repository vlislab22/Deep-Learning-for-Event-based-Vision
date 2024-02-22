# High Speed and High Dynamic Range Video with an Event Camera

Source: PAMI 2019

# Research Question

How to learn to reconstruct intensity images from event streams directly from data instead of relying on any hand-crafted priors?

# Motivation

1) Previous methods make strong assumptions about the statistics of natural images, leading to unrealistic reconstructions and artifacts. As a result,
high-quality video reconstruction from event data has so far not been convincingly demonstrated.

2) Recurrent network have shown great results in video reconstruction.

# Contribution

1) They propose a novel recurrent network that reconstructs video
from a stream of events.

2) They propose a novel temporal consistency loss to remove temporal artifacts.

3) Their method could be applied to two downstream problems: object classiﬁcation and visual-inertial odometry from event data.

# Weakness

1) The proposed temporal consistency loss may suffered from optic flow estimation errors, which is the reason why they design a adjustable parameter.

2) Their method do not focus on local textual information.

3) Unet-based network usually performs sub-optimal when it comes to the high-frequency information.
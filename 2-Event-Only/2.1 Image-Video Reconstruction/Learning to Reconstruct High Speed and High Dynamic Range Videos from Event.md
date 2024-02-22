# Learning to Reconstruct High Speed and High Dynamic Range Videos from Events

CVPR 2021

# Research Question

How to explore a better way of video reconstruction from events to reconstruct high speed HDR videos with high visual quality.

# Motivation

1) Previous works either suffer from unrealistic artifacts, or cannot provide sufficiently high frame rate.
2) The shortage of high-quality learning data.
3) Previous works either ignore temporal constraints, or use a suboptimal ﬂow warping loss. These also affect the video reconstruction quality.

# Main contribution

1) They collect a high-quality real dataset which contains paired high speed HDR videos and event streams of outdoor dynamic scenes.

2) They present a recurrent neural network
for the reconstruction of high speed HDR videos.

3) They propose a temporal consistency loss function to constrain the temporal discontinuity.

4) They design a special imaging system to collect the high speed and high bit-depth HDR videos with the corresponding event streams.

# Method

To perform high frame-rate video reconstruction, they embed event streams into **voxel grids** (also event frames) to utilize convolutional neural networks with event data.
The network mainly includes a shared feature extractor, a deformable convolution based alignment module, a convolutional recurrent fusion and reconstruction module, and a pretrained consistency loss module.

For the shared feature extractor, to encode consecutive frames into the same feature space (which is beneﬁcial for the alignment module), they simply employ several strided convolution
layers to encode the frames into feature space.

**Thinking Notes**: The shared feature extractor is only designed for encoding the consecutive frames into the same feature space. Is it possible to do alignment at the feature extraction stage?}

For the **Deformable convolution based alignment**, to alleviate the temporal discontinuity, previous method (optical ﬂow or ﬂow warping loss) cannot obtain an accurate ﬂow, and may cause motion artifacts due to erroneous ﬂow estimation. They employ pyramidal deformable convolutions for feature alignment, which learn offsets of normal convolutionkernels to obtain aligned features (as shown in Fig. \ref{M2}). 

**Thinking Notes**: The Deformable convolution based alignment may fail in high-speed and blurred scenes}

For the **Attentive fusion and reconstruction**, to further trace both spatial and temporal dependency, they propose a triple attention path to exploit the feature correlation along three
dimensions.

**Temporal consistency loss**. Previous works employed
flow warping error for temporal consistency loss, which leads to suboptimal due to the lack of accurate ﬂow estimation. They use a
UNet-like convolutional neural network to learn the mapping from frames to events.

**Thinking Notes**: The strategy provide a insight for temporal consistency loss. However, this two-stage training may make it hard to apply to real scenes.}

# Writing Skill

1) However, these works either suffer from XX, or XX.

2) In spite of that.

3) One possible reason for the insufficiency of reconstruction quality might be the shortage of high-quality learning data.

4) Although substantial efforts have been made to improve
the XX, it still remains unknown how XX.

5) This triggers us to develop proper.

6) In the experiment, we empirically set XX.
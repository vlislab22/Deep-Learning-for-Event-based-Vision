# Time Lens: Event-based Video Frame Interpolation

CVPR, 2020

## Background
There are various applications for video frames interpolation, primarily for videos with low frame rates, such as 30 to 50 frames per second, and the ability to increase frame rates to 500 or 1 000 frames per second.

## Research Question: 
Previous frame-based frame interpolation methods restrict the types of motions that can be modeled, leading to errors in highly dynamic scenarios.

Previous event-based frame interpolation methods can capture non-linear motions, but they suffer from ghosting and perform poorly in low-texture regions with few events. 

How to utilize frame-based and event-based approaches is the research question for this paper.

In addition, this paper releases a large-scale dataset for event guide frame interpolation.


## Previous Works
Previous work can be mainly divided into three categories.

(1)	Warping-based approach:
This method generates frames in between two keyframes by using optical flow and image warping. The linearity of the motion and the constancy of the brightness between keyframe frames are presumptions made by this approach.

(2)	Kernel-based approaches:
This technique views the insertion of video frames as a local convolution process, and the keyframes are used to create the convolution kernel.

(3)	Phase-based approaches:
In this technique, the neural network decoder explicitly predicts the phase decomposition of intermediate frames, treating video frame interpolation as a phase shift estimation issue.
However, these assumptions, such as linear motion and constant brightness change, are too strong.

In general, all video frame-based methods assume a simplified motion model, e.g., linear motion. Because there is no visual information available between video frames. This is the core flaw of frame-based approaches.
In addition, this assumption is also based on the premise that the brightness and changes are consistent, which significantly limits the application in other high-dynamic scenes.
1. non-linear motions between the input keyframes, 
2. changes in illuminations or motion blur. 
3. non-rigid motions and new objects appearing in the scene between keyframes.

## Weaknesses:
1.	No end-to-end learning.
2.	The alignment of frames is not considered. 
3.	The details are retrieved without considering the cross-modality.
4.	The frame insertion issue itself has not been thoroughly thought out.
5.	The registration of the dataset is biased.

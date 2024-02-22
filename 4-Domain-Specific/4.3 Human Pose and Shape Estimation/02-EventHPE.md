# EventHPE: Event-based 3D Human Pose and Shape Estimation

ICCV2021
    
## Research Question:
	How to infer 3D human shape from events as the major source of input: event are the sole source of input data to estimate 3D human shapes over time, given taht the beginning shape is known or extracted from the first frame of gray-scale image.

## Motivation:
  Event cameras is an emerging imaging sensor for caputring dynamics of moving objects as events, which motivates EventHPE in estimating 3D human pose and shape from the event signals.

## HighLight:
  EventHPE takes a steam of events and only the first frame of gray-scale image from an event camera as input.

## Methodology:
  Stage1: The events and optical flow are both closely related to human motions and optical flow can provide explicit geometric information to describe human body movements. Intuitively, a FlowNet is set in the first stage to give optical flow prediction without supervision.
  Stage2: ShapeNet is set at the second stage to estimate shape variations over time, given the events and the inferred optical flows as input.
  Besides, a flow coherence loss is proposed to enforce consistency of image-based flow (optical flow) and shape-based flow(vertices movement of human body shape), as both modalities are originated form the same human mition.
  
## Contributions:
(1) A new and challeging problem that estimating 3D human parametric shape mainly from events.

(2) A home-grown dataset is inroduced, referred as Multi-Modality Human Pose and Shape Dataset  (MMHPSD)


 

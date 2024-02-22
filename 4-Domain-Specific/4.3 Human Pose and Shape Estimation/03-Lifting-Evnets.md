# EventHPE: Lifting Monocular Events to 3D Human Poses

CVPRW2021
    
## Research Question:
   How to find human poses in asynchronous events? The first learning-based method for 3D human pose from a single stream of events is proposed.
  
## Motivation:
  Event cameras is an emerging imaging sensor for caputring dynamics of moving objects as events, which motivates EventHPE in estimating 3D human pose and shape from the event signals.
  
## Methodology:
  1. Process the event-camera stream to predict three orthogonal heatmaps per joint. Each heatmap is the projection of the joint onto orthogonal plane.
  2. Fuse the sets of heatmaps to estimate 3D localisation of the body joints.
  
## Contributions:
(1) A pipeline to predict human poses from a single stream of events;

(2) A new synthetic dataset for benchmarking event-based Human Pose Estimation;


 

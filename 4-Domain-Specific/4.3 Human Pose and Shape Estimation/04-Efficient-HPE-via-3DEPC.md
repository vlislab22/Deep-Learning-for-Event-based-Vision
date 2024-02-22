# Efficient Human Pose Estimation via 3D Event Point Cloud

3DV2022
    
## Research Question:
   How to estiamte 2D human pose directly from 3D event point cloud.
  
## Motivation:
  Predicting human keypoints drectly through events streams is scacely addressed in the state of the art. To fully unfold the potentioal of efficent HPE with DVS by processing events from evnet ponts sets, this work treats events as multidimensional data and predict the 2D joints for a single event camera via backbones established for point cloud processing.
  
## Methodology:
  1. Rasterized point cloud format of the event to reduce the number of evnets while retaining a considerable amount of evnet information.
  2. 3D learning backbone model and decoder: PointNet, DGCNN, Point Transformer and tow linear layer decoders.
  
## Contributions:
(1) The first work (claimed) of exploring the feasibility of estimating human pose from 3D event point clouds directly.

(2) A new event representation, rasterized event point cloud, is proposed which miantains the 3D features from multiple statistical cues and significantly reduces memory consumption and computational overhead with the same precision.


 

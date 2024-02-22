# EMVS: Event-Based Multi-View Stereo - 3D Reconstruction with an Event Camera in Real-Time

## Traditional Method without DL

IJCV 2018
    
## Research Question:
	We introduce the problem of event-based multi-view stetro (EMVS) for event camera, follow a Space-Sweep voting and maximization strategy to eatimate semi-dense depth maps at selected view-pointsw, and then merge the depth maps to build larger 3D models.

## Motivation:
	Inherent properties of event cameras: 
  (1) the ability to respond to scene edges, which naturally provide semi-dense geometric infromation without any pre-processing operation;
  (2) they provide cintinuous measurements as the sensor moves.

## Contributions:
(1) provide a justification of the choice of perspective sampling of space by analyzing the operation of event back-projectiuon;

(2) improve sturcture estimation by means of simple processing teachniques, such as bilinear voting in the Disparity Space Image and median filtering of the semi-dense depth map.


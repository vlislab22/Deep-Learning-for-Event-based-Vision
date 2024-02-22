# EventCap: Monocular 3D Capture of High-Speed Human Motions using an Event Camera

CVPR2020
    
## Research Question:
	How to utilize event cameras to solve the high frame rate requirement fro capuring fast human motions.

## Fundamental problem in tracking fast motions
  The high frame rate leads to excessive amounts of raw data and large bandwidth requirement for data processing.

## HighLight:
  EventCap, the first appraoch for 3D capturing of high-speed human motions using a single event camera. EventCap leverages the event stream and the low frame rate intensity images stream from the event camera in a joint optimization framework.

## Methodology:
  Stage1: Track the events in 2D space in an asynchronous manner and reconstruct the continuous spartio-temporal event trajectories between each adjacent intensity image frames.
  Stage2: Estimate the 3D motion of the human actor using a batch-based optimization algorithm.
  Stage3: Refine the captured high-speed motion based on the boundary information obtained from the asynchronous event stream.
  
## Contributions:
(1) The first monocular appraoch for event camera-based 3D human motion capture.

(2) A novel hybrid asynchronous batch-based optimization algorithm.

(3) An evaluation dataset for event camera-based fast human motion capture and provide high-quality motion capture results at 1000 fps.


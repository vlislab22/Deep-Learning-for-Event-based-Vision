# Video to Events: Recycling Video Datasets for Event Cameras

CVPR 2020 

## Research Question:
	How to obtain a large amount of event data for the training of deep learning based model?
	
## Motivation:
(1) Event camera simulator can be used to synthesize event data.    
(2) Virtually unlimited number of existing video datasets are readily available.    


## Contribution:
A framework to convert video dataset into event dataset by adaptive upsampling and event camera simulator(ESIM).
 

## Highlight:
(1) Generalization ability to real event data.

(2) Applying domain randomization by randomly sampling the contrast threshold during training.   

(3) Free of hand tuning on contrast threshold.

## Weakness:
Interpolation of video will bring blur into interpolated frames, and yields suboptimal results in the following events synthesis.

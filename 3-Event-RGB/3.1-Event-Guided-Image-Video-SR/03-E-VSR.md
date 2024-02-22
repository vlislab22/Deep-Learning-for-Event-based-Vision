# Turning Frequency to Resolution: Video Super-resolution via Event Cameras

CVPR, 2021

## Research Question: 
The authors found that a higher frequency, and hence a smaller pixel displacement between consecutive frames, tends to deliver favorable super-resolved results.
How to empty the event camera for video super-resolution base on above discovery this the key research question of this paper.

## Main Contributions:
1.	The first work about event based VSR.
2.	The Event-based VSR framework.
3.	Empty CED dataset for testing. 

## Motivation: 
1.	A higher frequency, and hence a smaller pixel displacement between consecutive frames, tends to deliver favorable super-resolved results.
2.	Event Cameras is a novel sensing device that responds instantly to pixel intensity changes and produces up to millions of asynchronous events per second. Events data can guide video frame insertion very well. 
3.	This paper proposes two-stage methods, the first stage aims to restore high frequency (HF) video, and the second stage aims to restore high resolution video from HF video.

## Weaknesses:
1.	Not an end-to-end approach.
2.	The technique is boring and does poorly extracting the essence of events.
3.	The visualization of experimental results is poor.
4.	The release of simulation results and experimental code is rejected by the author.


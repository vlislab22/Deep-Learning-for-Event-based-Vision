# Events-to-Video: Bringing Modern Computer Vision to Event Cameras / High Speed and High Dynamic Range Video with an Event Camera

CVPR 2019 / T-PAMI 2019

## Research Question:
    How to use video reconstruction to help object classification(and other downstream tasks)? 

## Motivation:
(1) Reconstructed videos can serve as an intermediate representation of event data.  

(2) Hand-crafted priors based reconstruction methods lead to unrealistic reconstructions and artifacts.

## Contribution:
(1) A new recurrent network reconstructs video from events stream.

(2) A perceptual loss to encourage reconstructions to follow natural image statistics.  

## Highlight:
(1) It can provide high framerate videos and high dynamic range reconstructions.

(2) Off-the-shelf computer vision algorithms can be applied to the reconstructions directly and consistently outperforms algorithms that were specifically designed for event data.

## Weakness:
This method is computationally less efficient than existing methods, such as HATS.

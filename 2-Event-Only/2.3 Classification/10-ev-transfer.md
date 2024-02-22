# Bridging the Gap between Events and Frames through Unsupervised Domain Adaptation

RA-L 2022

## Research Question:
    How to transfer a task to the target domain using unpaired data? 

## Motivation:
(1) The shortage of labeled datasets due to the novelty of event cameras.

(2) Large-scale datasets usually only comprise still images instead of video, and also no paired event data.

## Contribution:
(1) A task transfer method that makes the model available to detect and classify objects using labeled source image data and unlabeled target event data.

(2) Introducing a mapping from events to motion and content embeddings based on the event generation model.

## Highlight:
(1) The networks trained on labeled daylight images can be transferred to challenging nighttime scenarios.

(2) Splitting event features into content and motion features to help complement motion information during new event generation.

## Weakness
Generating event from a single image is an ill-posed problem as the missing motion information. 
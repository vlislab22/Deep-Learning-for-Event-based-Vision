# High Frame Rate Video Reconstruction Based on an Event Camera

IEEE TRANSACTIONS ON PATTERN ANALYSIS AND MACHINE INTELLIGENCE 2022

# Research Question

How to mitigate the limitations with current DAVIS cameras: 
1) Low Frame Rate Intensity Images;
2) Inherent Blur Effects.

# Main Contributions

1) They propose a multiple Event-based Double Integral (mEDI) model to restore better high frame rate sharp videos. The model is based on multiple images (even
blurred) and their corresponding events.
2) The mEDI is able to generate a sharp video under various types of blur by solving a single variable non-convex optimization problem, especially in low lighting condition and complex dynamic scene.
3) The frame rate of their reconstructed video can theoretically be as high as the event rate (200 times greater than the original frame rate in our experiment).

# Motivation

1) Event-only solutions , where the results tend to lack the texture and consistency of natural videos (especially for scenes with a static
background or a slowly moving background/foreground), as they fail to use the complementary information contained in low frame rate intensity images.
2) As the previous model is based on a single image, noise from the event data can easily degrade the quality of reconstructed videos, especially at transitions between images.

# Method

1) Multiple Event-Based Double Integral Model;
2) LU Decomposition

# Weaknesses

1) Extreme lighting changes, such as suddenly turning on/off the light, moving from dark indoor scenes to outdoor scenes. The relatively low dynamic range of the intensity image might degrade the performance of our method in high dynamic scenes;
2) Event error accumulation, such as noisy event data, small object motions with fewer events. Though they integrate over small-time intervals from the centre of the exposure time to mitigate this error, accumulated noise can reduce the quality of reconstructed images.
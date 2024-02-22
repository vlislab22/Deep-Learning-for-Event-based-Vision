# Time Lens++: Event-based Frame Interpolation with Parametric Non-linear Flow and Multi-scale Fusion

CVPR, 2022

## Context:
This method is an improvement over TimeLens.
	Previous methods still suffer from: 
(i)	brittle image-level fusion of complementary interpolation results, that fails in the presence of artifacts in the fused image, 
(ii)	potentially temporally inconsistent and inefficient motion estimation procedures, that run for every inserted frame and 
(iii)	low contrast regions that do not trigger events, and thus cause events-only motion estimation to generate artifacts.
(iv)	Previous methods were only tested on datasets consisting of planar and faraway scenes, which do not capture the full complexity of the real world.
Example: The Huawei P40 can record only 0.5s of 720p video with 1920 fps, which fills up its 2GB frame buffer.

## Research Question:
	How to efficiently sample for image warping from events and images? 

## Main Contribution：
This paper introducing multi-scale feature-level fusion and computing one-shot non-linear inter-frame motion.
They also collect the first large-scale events and frames dataset consisting of more than 100 challenging scenes with depth variations, captured with a new experimental setup based on a beam splitter.

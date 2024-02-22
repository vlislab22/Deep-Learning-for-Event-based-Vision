# Event Enhanced High-Quality Image Recovery

arXiv 2020

# Research Question

Is it possible to find an unfied framework to consider denoising, debluring and super-resolution simultaneously?

# Main Contributions

1) They propose an event enhanced degeneration model for the high-quality image recovery based on event cameras. Based on this, exploiting the framework
of sparse learning, they propose an explainable network, an event-enhanced sparse learning network, to recover the high-quality images from event cameras.
2) Without retraining process, they propose an easy method to extend the eSLNet for high frame-rate and high-quality video recovery.
3) They build a synthetic dataset for event camera to connect events, LR blurry images and the HR sharp clear images.

# Motivation

1) Exploiting the framework of sparse learning, the events and the low-resolution intensity observations can be jointly considered. 
2) Events record intensity changes at a very high temporal resolution, which can enhance the degeneration model effectively to represent motion blur
effect. The enhanced degeneration model provides a road to recover HR sharp and clear latent images from APS frames and their event sequences.
3) The framework of sparse could resist noise.

# Weaknesses
1) Experiments are insufficient.
2) Lack of innovation
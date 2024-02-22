# Learning to See in the Dark with Events

ICCV, 2021

## Research Question:
How to see in the dark by translating HDR events in low light to canonical sharp images?

## Method Details:
They proposed a novel unsupervised domain adaptation network that explicitly separates domain-invariant features (e.g., scene structures) from the domain-speciﬁc ones (e.g., detailed textures).
E_q is a day light-specific private encoder. E_c is a domain-shared encoder. R is a shared decoder. D is a domain discriminator. T is detail enhancing branch.
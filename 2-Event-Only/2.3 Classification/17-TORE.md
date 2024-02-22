# Time-Ordered Recent Event (TORE) Volumes for Event Cameras

T-PAMI 2022

## Research Question:
	How to build a kind of memory-efficient, information-preserving, and high-performance image-like representation for event data?
	
## Motivation:
(1) The mapping of asynchronous (i.e. sparse) camera events to synchronous (i.e. dense) framing data is irreversible and lossy.

(2) Spatial convolutions are not yet fully optimized for sparse data input.

## Contribution:
Time-Ordered Recent Events (TORE) Volume: Minimally-lossy, bio-inspired synchronous event representation for event camera data that support low- and high-level tasks.

## Highlight:
TORE volumes are available to compactly store raw spike timing information with minimal information loss, and contain “local memory” from past data.
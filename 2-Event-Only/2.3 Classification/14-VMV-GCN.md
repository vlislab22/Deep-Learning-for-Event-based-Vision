# VMV-GCN: Volumetric Multi-View Based Graph CNN for Event Stream Classification

RA-L 2022

## Research Question:
    How to aggregate neighborhood features by considering relationships between vertices in event-based graph learning?
    
## Motivation:
(1) Existing methods that utilize frame-based representation are not fit with the sparsity of event data.
 
(2) GNN-based method relies on original input coordinates of vertices to find neighbor vertices and aggregate their features, which is not sufficient.

## Contribution:
(1) A novel event-based voxel feature encoding module called VMVF to learn spatial semantics and motion information from voxel-wise multi-view.

(2) A voxel-wise dual-graph construction strategy to represent relationships between event voxels.

(3) Dynamic neighborhood feature learning module (DNFL) to aggregate features and update coordinates of vertices dynamically layer by layer.

## Highlight:
(1) Grouping vertices by considering the proximity both in the original input and feature space.

(2) Voxelizing the event stream and selecting representative voxels through motion-sensitive voxel sampling.

## Weakness:
It doesn't consider asynchronization of the events.

# N-ImageNet: Towards Robust, Fine-Grained Object Recognition with Event Cameras

ICCV 2021

## Research Question:
	How to conduct robust and fine-grained object recognition on a large-scale event-based dataset?
	
## Motivation:
(1) A need for the large-scale fine-grained benchmark on event-based dataset.  
(2) New representation for robust object recognition in various environmental conditions.

<!--###Building Dataset:
Event camera datasets includ **real-world object** ones and **monitor-displayed image** ones.  
The former suffers from a lack of number of labels and difficulty to acquire fine-grained labels of real-world recordings. While monitor-displayed image datasets contain abundant labels from their original image datasets.
### 
-->


## Contribution:
(1) N-ImageNet, the largest fine-grained event camera dataset to date, thus serving as a challenging benchmark.

(2) Nine validation datasets to test the robustness of event-based object recognition algorithms amidst changes in **motion** or **illumination**.

(3) DiST (Discounted Sorted Timestamp Image), an event camera representation exhibiting enhanced robustness in diverse environment changes.
 

## Highlight:
(1) First quantitatively investigate the consequences caused by various environmental conditions on event-based object recognition algorithms.  

(2) Pretraining on N-ImageNet improves the performance of event-based classifiers and helps them learn with few labeled data.  

(3) The representations using relative timestamps (sorted time surface and DiST) outperform those using raw timestamps.

## Weakness:
The performance of DiST not outperforms that of EST which is learned with MLP.  
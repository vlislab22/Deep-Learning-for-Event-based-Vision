# Ev-TTA: Test-Time Adaptation for Event-Based Object Recognition

CVPR 2022

## Research Question:
    How to reduce the domain gap when event-based algorithm applied in challenging real-world condition(e.g., low lighting and extreme motion)?
    
## Motivation:
(1) Existing event-based recognition algorithms suffer from performance deterioration under extreme conditions due to significant domain shifts.

(2) Since it is difficult to manually collect labeled data in a wide variety of external conditions, an adaptation strategy is necessary to fully leverage the potential of event cameras.

## Contribution:
(1) A novel test-time adaptation objective based on temporal consistency.

(2) A noise removal mechanism for low-light conditions utilizing spatial consistency.

(3) Comprehensive evaluation of Ev-TTA in event-based object recognition using a wide range of event representations.

## Highlight:
(1）The method does not require labeled data from the target domain and can operate in an online manner.

(2) Ev-TTA shows universal improvements across all event representations tested for a wide range of external conditions.
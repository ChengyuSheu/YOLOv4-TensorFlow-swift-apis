# YOLOv4-TensorFlow-swift-apis
This is a minimum implementation of YOLOv4 in Swift for TensorFlow, S4TF. Everything, including helper functions, is implemented in Swift. This repository is a complete example for researchers/engineers to get a first insight of pure S4TF, even though it supports Python libraries =).

Requirement:
1. Swift for TensorFlow, 0.9. (used a lot of hacked tricks)
2. swift-jupyter + SPM

Achieved:
1. .weights file loading supported
2. EXACT OUTPUT like Darknet
3. faster than Darknet on CPU

TODO:

0. refactor code (it's my first swift project, hacky things need to be improved.
1. post-processing
2. visualization
3. training

Implemented NN components:
1. SPP, Spatial Pyramid Pooling
2. CSP, Cross-Stage-Partial-connections
3. mish, activation function
4. Darknet-padding methods

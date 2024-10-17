---
date: 2024-10-12
aliases:
  - DL
---

Status: #child 
Tags: [[AI and Applications]] [[Computer]] [[Neural Networks]]
# Deep Learning
A subclass/class of [[Neural Networks|NN]] with many layers that can automatically discover patterns in data

It can handle a lot of amounts of data and complex computation, sometime even better than human
## Depth
Multiple layers (3 or more) that transform input data into abstract and composite representations
## Process 
Input image → Pixels → Edges → Textures → Parts → Objects
## Components
1. [[Neural Networks]]
2. Layers
3. Input data and target
4. [[Activation Function]]
5. Loss function
6. Optimized algorithms
## Types
1. Feedforward Neural Network (FNN) - Data flows in one direction
2. Convolutional Neural Network (CNN) - Use in image recognition and processing
3. Recurrent Neural Network (RNN) - Uses in sequence prediction (E.g. Language processing)
## Convolutional filter
## Pooling filter
## Framework
### Tensor Flow
 Developer: Google Brain

Primary Language: Python, C++, JavaScript

Execution: Static Computational Graph (Graph Mode)

Deployment: TensorFlow Serving, TensorFlow Lite, TensorFlow.js
### PyTorch
Developer: Facebook AI Research

Primary Language: Python, C++

 Execution: Dynamic Computational Graph (Eager Execution)
 
 Deployment: TorchServe, ONNX
 
## Challenges
1. Overfitting - model learn the details and notes in the training data that impact negatively to the performance on new data
2. Computation Demands - Hardware require for training need to have good performance
3. Data quality - Dependence on large, well-annotated datasets
## Processors needed
1. CPU (Central Processing Unit)
- General-purpose computing
-  Few cores (2-16 cores), optimized for sequential tasks
2. GPU (Graphics Processing Unit)
- Parallel processing, graphics & computation
- Thousands of cores, optimized for parallel tasks
3. TPU (Tensor Processing Unit)
- Specialized for neural network tasks
- Matrix processors, optimized for tensor operations
# References
[[Applications of Deep Learning]]
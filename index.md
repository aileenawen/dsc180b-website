# DSC180B Project



## Introduction

"""
1. What is the motivating question/problem being addressed?  
3. Why should the reader care? (Significance)
4. How are you approaching the problem? Why is it reasonable? 
"""

Our problem of interest for this project is to investigate ways to reduce the size of machine learning models while maintaining the same functionalities and performances as before. For the first half of the project, we investigated and studied BNNs through the paper “Quantized Neural Networks: Training Neural Networks with Low Precision Weights and Activations”. We focused on rebuilding the BNNs according to the method mentioned in the paper with more modernized libraries, namely Pytorch and Tensorflow, last quarter. In the second half of the project, we shifted our focus on investigating how does using different numbers of bits affects the accuracy of our models, especially for RNN and LSTM, since the paper mentioned how RNN and LSTM did not work well for 2 bits and needed 4 bits instead. Furthermore, we will also investigate how does using other functions, other than the HardTanh function, during backpropagation affect NNs’ accuracy, size, and power consumptions

Our work is significant because we believe that the ability to utilize NNs on smaller devices will revolutionize the industry, and we would like to be part of this world-changing process while diving deep into studying some of the cutting-edge models and optimization methods. 



## Method and Approach

### First Quarter

"""
Describe how you approached the problem
A description of your methods describes how your approach is effective and/or novel.
How in-depth the explanation depends on the audience!
"""

In the first part of the project, we studied the methods introduced in the paper “Quantized Neural Networks: Training Neural Networks with Low Precision Weights and Activations”. We also reproduced the methods and experiments described in the paper using two more modernized libraries, Tensorflow and PyTorch, instead of Theano which was what the paper originally used. 

#### Investigation & Analysis

#### Results



### Second Quarter

"""
Describe how you approached the problem
A description of your methods describes how your approach is effective and/or novel.
How in-depth the explanation depends on the audience!
"""

During the second half of the project, we hope to explore how using different numbers of bits affects the accuracy of our models, especially for RNN and LSTM, since the paper mentioned how RNN and LSTM did not work well for 2 bits and needed 4 bits instead. Furthermore, we will also investigate how other functions, other than the HardTanh function, during backpropagation or a different combination of several layers and Neuron sizes might affect NNs’ accuracy, size, and power consumptions.

#### Experiments

#### Results



## Conclusion and Impact

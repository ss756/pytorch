# pytorch

Curated tutorials to understand why Pytorch is the Deep Learning Framework of the Future
Pytorch is a open source machine learning library used primarily for applications such as computer vision and natural language processing.
It is easy to use and gives a pythonic like feel. Promotes higher developer productivity and enables easier debugging like Pycharm. Python's pdb and ipdb tools can be used for this kind of debugging in Pytorch. Data 
parallelism is supported by python. Using this feature, Pytorch can distribute computational work among multiple CPU or GPU cores). This feature of Pytorch allows us to use torch.nn.DataParallel to wrap any module and helps us to do parallel processing over the batch dimension. Pytorch is a batteries included framework as it supports Dyanamic Computation Support Graphs, which means the network behaviour can be changed programmatically at runtime. This facilitates more efficient model optimization and gives Pytorch a major advantage over other ML frameworks, which treat neural networks as static objects. Pytorch alse boasts of a newer hybrid frontend. We have 2 modes of operation:
1. Eager Mode 
2. Graph Mode 

We generally use eager mode for R&D purposes as this mode provides flexibility and ease of use. And we generally use this graph mode for production, as this provides better speed, optimization and functionality in a C++ runtime environment. 

Useful libraries of Pytorch...

1. gpytorch : It is a highly efficient and modular implementation with GPU acceleration. It is implemented in pytorch and combines gaussian processes with core deep neural networks. 
2. botorch : It is a pytorch related library used for Bayesian Optimization. 
3. allenNLP : It is a open sourced NLP research library built with pytorch 
There are countless more libraries 


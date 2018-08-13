# Code for Rank-1-CNN 

Rank1-MNIST.ipynb : the code for the Rank-1 network on the MNIST dataset. 
Rank1(Cifar10)-size32.ipynb : the code for the Rank-1 network on the CIFAR10 dataset. 

Here, we are testing on the same network structure as used in the training stage.
However, as we mentioned in the paper, in the test time we can filter the input
with consecutive 1-D filters, where we can use the trained 1-D vectors p, q, and t as the 1-D filters.
This results in a faster inference time.

(This page will be updated)

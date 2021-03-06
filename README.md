# Tensorflow essentials
A trip through the essentials of Tensorflow. 
Much of what I know comes from the amazing book **Hands-On Machine Learning with Scikit-Learn and TensorFlow**. 
The idea is to go from Tensorflow 1.x to Tensorflow 2.x, while exposing some essential concepts in Tensorflow development. 

## 1. Building a DNN from scratch
> Yeah, this notebook is not as exciting as launching a rocket into space or discussing about quantum physics.
What I would like to show though is the level of detail and attention that one needs to put into building even the simpler version of such powerful models. In a nutshell, the message here is to be responsible even when the task seems fairly easy.

## 2. Distributed computation 
> Tensorflow offers the user different ditributed computation tools. In the notebook I explore the parallelization of simple graphs across several GPUs on a single machine. Parallelizing across multiple servers using Tensorflow is hard (and you must have a cluster at disposal). Other frameworks such as Apache MXnet offer fairly easier tools to parallelize the computation over clusters of machines. 

## 3. CNNs 
> Time to explore the building blocks of a Convolutional Neural Network from a low level implementation perspective (```@tensorflow 1.x```). Here we put together some of the basics of the ```Tensorflow``` library, while keeping the focus on some good common practices (```name scopes```,```variable initialization ```,```summaries```,...)-

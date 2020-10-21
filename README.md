# WassersteinQA
NLP Project 2020 - UCL DSML

# Overview

Defining a distance between distributions or datasets is crucial for various machine learning tasks including transfer learning and generalization from one dataset to another. Current methods used in Natural Language Processing (NLP) usually rely on different parameters that have to be optimised or require to train a model. With the recent success of Optimal Transport in computer vision, several approaches have proven their efficiency in identifying similarities between distributions. Some methods are used in NLP for document representation. However, Optimal Transport is still relatively new when it comes to comparing entire text datasets. This can be explained by the fact that the task becomes significantly more complex as the distribution of each dataset strongly depends on the embedding approach. In this paper, we propose a new method based on the Wasserstein Optimal Transport distance which (i) evaluates the distance between Question-Answering (QA) datasets, (ii) is efficient and (iii) is based on strong theoretical footing. (iv) We validate the correctness of our method by showing its compatibility with a transfer learning task.

# Demo Notebook

[Link to colab notebook](https://colab.research.google.com/drive/1-DXF6nrJRD0B_bf8jwDesYlZf49gBK4t?usp=sharing)

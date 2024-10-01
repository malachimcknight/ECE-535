## ECE 535
## Project 5 — Federated Learning on Heterogeneous Sensor Data

### Team members
* Malachi McKnight
> Role: setup, software, research, algorithm testing
* Om Tank
> Role: writing, research, algorithm development
* Kenneth Lin
> Role: research, algorithm design, software

## Motivation
* Federated Learning is a popular machine learning paradigm that allows multiple
parties to collaboratively train a joint (global) neural network without exposing their private data.
However, the performance of the global model is impacted by the heterogeneity, i.e., skewness of
the data of each individual participant.

## Design goals
* Characterize the impact of heterogeneity on FL. Then do the same characterization under
adversarial conditions.

## Deliverables
* Understand federated learning and heterogeneity.
* Implement FL with different datasets and different levels of heterogeneity.
* Include some adversarial attacks and perform the same characterization.
* What do we observe in adversarial vs. non-adversarial settings? Why do we think the impact of heterogeneity is different in both settings?

## System blocks

## Hardware/Software requirements
* Python
* Laptop with CUDA-enabled GPU
* Google Colab

## Project timeline
* Project selection — September 29

## References
* Communication-Efficient learning of deep networks from decentralized data. [[Link]](http://proceedings.mlr.press/v54/mcmahan17a/mcmahan17a.pdf)
* Example codes for different data partionings [[Link 1]](https://github.com/SMILELab-FL/FedLab/tree/master/tutorials/Datasets-DataPartitioner-tutorials) [[Link 2]](https://arxiv.org/pdf/2303.17580)

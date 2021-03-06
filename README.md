# Meta Reinforcement Learning

This repository implements the meta-reinforcement learning algorithm for a variety of cognitive tasks using two separate network architecture.

## Table of contents
* [Introduction](#introduction)
* [Repository Structure](#repository-structure)
* [Reading](#reading)
* [Contributing](#contributing)
* [Contact](#contact)

## Introduction

Meta-reinforcement learning(meta-RL) simply put is a method that learns to perform reinforcement learning tasks using meta-learning. More specifically, a meta-RL model learns to perform a family of tasks by adjusting the network weights during training. The model is then tested on a different (but part of the same family of problems) task than training. It learns to perform the test task by adjusting its hidden state without adjusting the network weights. The basic idea of meta-RL was simultaneously proposed in [Wang et al. 2016](https://arxiv.org/abs/1611.05763) and [Duan et al. 2017](https://arxiv.org/abs/1611.02779). These papers were followed by [Wang et al. 2018](https://www.nature.com/articles/s41593-018-0147-8) where the authors compare the results of the neuroscience experiments to that of the meta-RL model and suggest explanations to diverse range of experimental findings.

In this project, we will implement all the cognitive tasks that were implemented in the [Wang et al. 2018](https://www.nature.com/articles/s41593-018-0147-8) paper using Tensorflow 2. We will also implement and analyse a different version of the two-armed bandit task where the reward and action are by a fixed delay period using two separate network architectures.

## Repository Structure

Here is what each file or folder in the repository contains:

Folder:

1. Training - This folder contains the training data for the various cognitive tasks. This folder is divided further into folders named based on which task the training datas belong to.

Files:

1. bandit_train.ipynb - This file implements the training part of the meta-RL model for the bandit 
task.

## Reading

Refer to the resources provided below to better your understanding of meta-RL algorithm and its implementation. 

1. https://www.nature.com/articles/s41593-018-0147-8

2. https://arxiv.org/abs/1611.05763

3. https://arxiv.org/abs/1611.02779

4. https://lilianweng.github.io/lil-log/2019/06/23/meta-reinforcement-learning.html

5. https://www.youtube.com/watch?v=LnXgs73OUjE

## Contributing

Here are a few ways you could help contribute to this repository.

1. Add implementations of the same or a different cognitive task but please make sure to add comments wherever necessary. Please make sure to add comments wherever necessary. Additionally, make sure to follow the current organization of the repository while adding the codes and results.

2. Add or suggest additional analysis (by opening an issue) for the tasks already implemented on the repository.

3. Report bugs by opening an issue.

4. Add additional resources to the reading section.

Note: This is not an exhaustive list. Please feel free to suggest any other ideas to contribute towards the development of this repository. 

## Contact

Email: aavinash@ucdavis.edu
Linkedin: http://www.linkedin.com/in/baidyaavinash

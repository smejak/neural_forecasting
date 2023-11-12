# Forecasting Neural Responses in a Coherence Classification Task
Comparing HMMs and RNNs in forecasting neural responses performing a coherence classification task.

## Overview
The dataset comprises neural activity from 157 neurons in a rat's primary visual cortex, collected over seven days, provided by the courtesy of Dr. Adam Shai and the [Schnitzer lab](pyramidal.stanford.edu). During the task, a rat is shown a screen with dots moving either left or right with varying levels of coherence. The rat needs to correctly classify the direction to receive a reward. The dataset includes stimuli, coherence levels, behavioral responses, and neural activities.

## Models
We investigate two model types: state-space models and deep learning models, specifically Hidden Markov Models (HMMs) and Recurrent Neural Networks (RNNs).

The libraries used for defining and training these models include [`ssm`](https://github.com/lindermanlab/ssm) and [PyTorch](https://pytorch.org/).

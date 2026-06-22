# Aggregation Choices in Graph Neural Networks for Image-Derived Patch Graphs

Investigating the effect of aggregation function choice (mean, sum, max) 
in GraphSAGE and GIN on image-derived patch graphs constructed from the 
HAM10000 dermoscopic image dataset.

## Overview
This repository contains the code for a study investigating how aggregation 
function choice affects the generalization performance of GNNs on 
image-derived patch graphs.

## Models Compared
- GraphSAGE with mean, sum, and max aggregation
- GIN with fixed and learnable epsilon

## Dataset
HAM10000 dermoscopic image dataset — 10,015 dermatoscopic images across 
seven diagnostic categories.
Available at: https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000

## Requirements
- Python 3.12
- PyTorch
- PyTorch Geometric
- torchvision
- scikit-learn
- Google Colab Pro with T4 GPU

## Results
See the report for full experimental results and analysis.

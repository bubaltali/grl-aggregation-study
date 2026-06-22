# grl-aggregation-study
Investigating the effect of aggregation function choice  (mean, sum, max) in GraphSAGE and GIN on image-derived  patch graphs constructed from the HAM10000 dermoscopic  image dataset.

# Aggregation Choices in Graph Neural Networks 
# for Image-Derived Patch Graphs

## Overview
This repository contains the code for a study investigating 
how aggregation function choice affects the generalization 
performance of GNNs on image-derived patch graphs.

## Models Compared
- GraphSAGE with mean, sum, and max aggregation
- GIN with fixed and learnable epsilon

## Dataset
HAM10000 dermoscopic image dataset
Available at: https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000

## Requirements
- Python 3.12
- PyTorch
- PyTorch Geometric
- Google Colab Pro (recommended)

## How To Run
1. Open the notebook in Google Colab
2. Set up Kaggle credentials in Cell 4
3. Run all cells in order
4. Results are saved automatically to Google Drive

## Results
See the report for full experimental results and analysis.

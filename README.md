# Aggregation Choices in Graph Neural Networks for Image-Derived Patch Graphs

Investigating the effect of aggregation function choice (mean, sum, max) 
in GraphSAGE and GIN on image-derived patch graphs constructed from the 
HAM10000 dermoscopic image dataset.

## Overview
This repository contains the code for a study investigating how aggregation 
function choice affects the generalization performance of GNNs on 
image-derived patch graphs. The study compares GraphSAGE variants with 
mean, sum, and max aggregation against GIN with fixed and learnable epsilon.

## Models Compared
- GraphSAGE with mean aggregation
- GraphSAGE with sum aggregation
- GraphSAGE with max aggregation
- GIN with fixed epsilon
- GIN with learnable epsilon

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
- matplotlib
- seaborn
- pandas
- tqdm
- Google Colab Pro (recommended)
- GPU with at least 15GB VRAM recommended

## How To Run
1. Open the notebook in Google Colab
2. Mount your Google Drive
3. Set up Kaggle credentials in Cell 4
4. Run all cells in order
5. Results and models are saved automatically to Google Drive

## Hardware Used
- Google Colab Pro
- NVIDIA Tesla T4 GPU
- 51GB RAM

## Results
See the report for full experimental results and analysis.

# CSE425 VAE Project

This repository contains the implementation and experiments for the
CSE425 Neural Networks course project.

## Project Title
**Unsupervised Multimodal Music Emotion Clustering using a Convolutional Conditional VAE**

## Overview
The project explores unsupervised clustering of music emotions using
audio spectrograms and lyrical information. A Convolutional Conditional
Variational Autoencoder (CVAE) is used to learn latent representations,
which are evaluated through multiple clustering approaches.

## Methods
- Convolutional Conditional Variational Autoencoder (CVAE)
- PCA + K-Means
- Autoencoder + K-Means
- Multimodal fusion with SBERT lyrics embeddings

## Evaluation Metrics
- Silhouette Score
- Adjusted Rand Index (ARI)
- Normalized Mutual Information (NMI)
- Cluster Purity

## Dataset
We use the **MERGE (Multimodal Emotion Recognition in Music)** dataset.

Dataset link:
https://zenodo.org/records/13939205

> The dataset is not included in this repository due to size constraints.

## Repository Structure

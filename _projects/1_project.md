---
layout: page
title: Hypergraph Semi-Supervised Learning
description: Novel hypergraph-based ML algorithms for semi-supervised & multi-label classification — published at ICPR 2024 & CODS-COMAD 2024
img: assets/img/projects/hypergraph.jpg
importance: 1
category: research
related_publications: true
---

Developed two novel hypergraph-based machine learning algorithms that exploit **higher-order relationships** in data (beyond pairwise graph edges) for semi-supervised and multi-label classification tasks.

## Key Contributions

- **Improved Hypergraph Laplacian SVM** — a semi-supervised SVM that uses an improved hypergraph Laplacian as a regularizer, enabling effective use of unlabeled data
- **Hypergraph LS-TSVM** — a least squares twin SVM extended with hypergraph regularization for multi-label scenarios
- **Imbalanced Multi-label Classification** — a hypergraph framework with label-specific features to handle class imbalance

## Results

Delivered superior performance over state-of-the-art baselines on:
- UCI ML Repository benchmark datasets
- MNIST Fashion
- NLP text classification datasets

Implemented high-performance retrieval pipelines using **FAISS** vector storage for efficient nearest-neighbour search in high-dimensional feature spaces.

## Publications

{% cite nirwal2024improved %}
{% cite nirwal2024lstsvm %}
{% cite nirwal2024imbalance %}
{% cite nirwal2025hypergraph %}

## Tech Stack

`Python` · `Scikit-learn` · `PyTorch` · `FAISS` · `MATLAB` · `NumPy` · `SciPy`

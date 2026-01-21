# Final Project: Synthetic Data Generation and Privacy Evaluation

This folder contains my individual contributions to the final project, focused on synthetic data generation and privacy-aware evaluation.

## Overview

The final project explored whether synthetic data could preserve predictive signal while reducing privacy risk in large-scale click-through data.

My work focused on:
- Data preprocessing and memory optimization
- Synthetic data generation using REaLTabFormer
- Evaluating privacy and fidelity tradeoffs

## Files

- preprocessing_pipeline.ipynb
  Implements data pruning, feature engineering, and memory reduction for large tabular datasets.

- realtabformer_generation.ipynb
  Trains REaLTabFormer models on task-specific subsets. Includes custom fixes to the REaLTabFormer package and GPU-aware training adjustments.

- privacy_evaluation.ipynb
  Evaluates synthetic data using distributional comparisons and downstream utility metrics.

## Key Technical Challenges

- First-time implementation of synthetic data generation
- Debugging and modifying a third-party library to resolve training issues
- Managing long training times and GPU crashes by tuning hyperparameters and batch sizes
- Addressing severe class imbalance by partitioning the dataset into task-level subgroups

## Tools

- Python, pandas, NumPy
- XGBoost
- REaLTabFormer
- joblib for caching
- Google Colab with GPU acceleration

# Stats414
UCLA Stats 414 Predicting Click Through Rate

# Synthetic Data Generation and Privacy Evaluation for Click-Through Prediction

This repository contains my individual contributions to a group project completed for STATS 414. My work focused on data preprocessing, synthetic data generation using REaLTabFormer, and privacy evaluation of generated datasets.

The project explores whether synthetic data can preserve utility for downstream modeling while reducing privacy risk in large-scale, highly imbalanced click-through rate data.

## Project Overview

The original dataset comes from a large advertising click-through prediction task with severe class imbalance. Due to scale and privacy constraints, the project explored whether synthetic data could be used as a proxy for real user-level data.

My contributions span:
- Data pruning and preprocessing for large tabular datasets
- Feature engineering and memory optimization
- Training REaLTabFormer models on task-specific subsets
- Evaluating privacy and fidelity tradeoffs in synthetic data

## Repository Structure

- data/: Dataset access instructions
- code/midterm/: Feature importance analysis using XGBoost
- code/final/: Preprocessing, synthetic data generation, and privacy evaluation
- slides/: Final and midterm presentation decks

## Dataset

The raw data is publicly available via Kaggle:
https://www.kaggle.com/datasets/xiaojiu1414/digix-global-ai-challenge

See data/README.md for instructions on downloading the dataset via API.

## Notes on Scope

This repository contains only the code I personally authored. Other group members worked on additional models such as logistic regression and ensemble classifiers, which are not included here.

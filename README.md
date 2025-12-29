# Comparative Analysis of Sentiment Analysis Models

## Author
Fadi Awawdeh

## Project Overview
This project presents a comparative study of sentiment analysis models across
multiple paradigms: rule-based, classical machine learning, deep learning, and
transformer-based approaches.

The goal is to evaluate accuracy, efficiency and practical trade-offs across
datasets with different sizes and sentiment complexity.

## Datasets
- IMDB Movie Reviews (binary sentiment)
- Stanford Sentiment Treebank (SST-5)
- Amazon Customer Reviews (binary sentiment)

## Models Evaluated
- Rule-based: VADER
- Classical ML: Logistic Regression, Naive Bayes 
- Deep Learning: 1D CNN
- Transformer-based: RoBERTa

## Methodology
All models were evaluated using consistent preprocessing, train-test splits,
and evaluation metrics. Baseline models used default configurations, while
improved models applied hyperparameter optimization.

## Results
Results show that classical models such as Logistic Regression achieve near-
optimal performance on large-scale binary sentiment tasks, while transformer
models provide advantages primarily in fine-grained sentiment classification.

## Repository Structure
- notebooks/: Jupyter notebooks for each dataset
- results/: Tables and figures used in the report
- presentation/: Final presentation slides

## Reproducibility
Install dependencies using:

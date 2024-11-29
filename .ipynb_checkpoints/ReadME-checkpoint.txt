# Naive KNN vs K-D Trees: Time Complexity and Performance Comparison

This repository showcases a detailed comparison between the Naive K-Nearest Neighbors (KNN) classifier and a custom-built K-D Tree implementation. The project involves building models for spam email classification using real-world data and evaluating their efficiency on various datasets.

---

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Dependencies](#dependencies)
4. [Implementation Details](#implementation-details)
5. [Usage Instructions](#usage-instructions)
6. [Results and Insights](#results-and-insights)
7. [Future Enhancements](#future-enhancements)

---

## Overview

The primary objective of this project is to:
1. Compare the execution time and performance of Naive KNN and K-D Tree implementations.
2. Analyze the impact of dataset size and feature selection on model efficiency.
3. Develop a robust feature extraction pipeline for spam email classification.

Key operations include:
- Feature engineering on raw email data.
- Dimensionality reduction techniques (Chi-square feature selection and optional PCA).
- Implementation of custom Naive KNN and K-D Tree models from scratch.
- Performance evaluation on time complexity and accuracy metrics.

---

## Features

### 1. **Feature Engineering**:
- Extracts custom features such as `char_count`, `word_count`, `capitalized_words`, `suspicious_greeting`, and `sentiment_polarity` from email text.
- Constructs a TF-IDF matrix to represent textual data numerically.

### 2. **Models Implemented**:
- **Naive KNN**: A straightforward KNN classifier.
- **Custom K-D Tree**: Optimized for efficient nearest-neighbor searches with adjustable parameters (leaf size, distance metrics).

### 3. **Performance Metrics**:
- Execution time for building and querying K-D Trees.
- Accuracy scores for classification tasks.

### 4. **Visualization**:
- Bar charts to illustrate the time complexity of Naive KNN and K-D Tree across varying dataset sizes.

---

## Dependencies

The following Python libraries are required for this project:
- `numpy`
- `pandas`
- `nltk`
- `textblob`
- `matplotlib`
- `joblib`

Install dependencies using:
```bash
pip install numpy pandas nltk textblob matplotlib joblib

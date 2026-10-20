# Wine Type Classification (Mission 1)

## Overview
Predicts the grape cultivar (3 classes) of a wine from 13 chemical measurements. Compares a Decision Tree and K-Nearest Neighbors using accuracy and confusion matrices.

## Dataset
UCI Wine dataset, bundled with scikit-learn (sklearn.datasets.load_wine): https://archive.ics.uci.edu/dataset/109/wine

## Setup
pip install pandas matplotlib scikit-learn jupyter
jupyter notebook wine_classification.ipynb

## Results
- Decision Tree accuracy: 0.944
- KNN accuracy: 0.972
- KNN performed better (features were scaled for KNN).

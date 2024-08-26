# Implementation of Decision Trees on Diverse Datasets

This project demonstrates the implementation of a Decision Tree classifier to predict student placements based on CGPA, resume score, and package offers.

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Dependencies](#dependencies)
4. [Model Training](#model-training)
5. [Making Predictions](#making-predictions)
6. [Evaluating the Model](#evaluating-the-model)
7. [How to Run](#how-to-run)

## Overvie

The project uses a Decision Tree classifier with entropy as the criterion to predict whether a student gets placed based on features like CGPA, resume score, and package offers.

## Dataset

```python
import pandas as pd

df = pd.DataFrame([
    [8, 8, 4, 1],
    [7, 9, 5, 0],
    [6, 10, 6, 1],
    [5, 12, 7, 1]
], columns=['cgpa', 'resume_score', 'package', 'placed'])

print(df)

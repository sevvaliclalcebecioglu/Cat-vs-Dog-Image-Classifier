# 🐱🐶 Cat vs Dog Image Classification

This project is a solution to the **Kaggle Cat or Dog Image Classification Challenge**.

## Overview

- Build a CNN or Transfer Learning model to classify images as Cat (0) or Dog (1)
- Generate `submission.csv` for Kaggle evaluation

## Dataset

- Kaggle: [Cat or Dog Image Classification Challenge](https://www.kaggle.com/competitions/cat-or-dog-image-classification-challenge)
- Dataset contains 8005 images (JPEG)
- No labels provided — use pseudo-labels or pretrained models

## How to Run

### Using Kaggle Notebook
1. Load images using `ImageDataGenerator`
2. Train a CNN / TL model or use pretrained model
3. Predict and generate `submission.csv`

### Using Streamlit App
```bash
streamlit run app.py

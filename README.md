# Assignment 5a - Machine Learning in Python

An end-to-end machine learning project on the Iris dataset using Python, following the tutorial by Jason Brownlee.

## Source
Tutorial: https://machinelearningmastery.com/machine-learning-in-python-step-by-step/
Author: Jason Brownlee

## Contents
```
Assignment5a-ML-Python/
+-- manual/
|   +-- ML_python.ipynb  # Hand-built ML notebook
|   +-- environment.yml
+-- ai/
|   +-- ML_python.ipynb      # AI-generated ML notebook
|   +-- environment.yml
|   +-- PROMPTS.md
|   +-- README_AI.md
+-- README.md
```

## How to Run
conda env create -f manual/environment.yml
conda activate ml-python
jupyter lab

Then open manual/ML_python.ipynb (or ai/ML_python.ipynb for the AI version).

## Steps
1. Import libraries and check versions
2. Load Iris dataset
3. Summarize dataset
4. Visualize dataset
5. Evaluate 6 algorithms with cross-validation
6. Make predictions on validation set

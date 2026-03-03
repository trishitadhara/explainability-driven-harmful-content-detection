# Beyond Accuracy: Explainability-Driven Analysis of Harmful Content Detection

This repository contains code and artifacts for the paper:

**Beyond Accuracy: An Explainability-Driven Analysis of Harmful Content Detection**  
Accepted for oral presentation at TrustNet 2026 (Springer LNCS format).

## What this repo includes
- Fine-tuning a RoBERTa-base classifier on Civil Comments (binary toxicity)
- Evaluation (accuracy, AUC, precision/recall/F1, confusion matrix)
- Post-hoc explanations:
  - Shapley Additive Explanations (SHAP)
  - Integrated Gradients (Captum)
- Example-level analysis of TP / FP / FN cases and failure modes

## Quickstart (Colab)
The entire pipeline can be run using notebook:
explainable ai-harmful content detection.ipynb


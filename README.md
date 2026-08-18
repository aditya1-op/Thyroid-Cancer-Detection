# Thyroid Cancer Recurrence Prediction

## Overview

This project focuses on predicting recurrence in differentiated thyroid cancer using machine learning and explainable artificial intelligence (XAI).

The workflow combines data preprocessing, feature selection using the Frog-Snake prey-predation Relationship Optimization (FSRO) algorithm, machine learning model development, ensemble learning, deep tabular models, and explainability analysis.

The primary objective is to develop an accurate and interpretable prediction pipeline for thyroid cancer recurrence.

---

## Dataset

The project uses the **Differentiated Thyroid Cancer Recurrence** dataset.

- **Samples:** 383
- **Predictor variables:** 16
- **Target:** `Recurred` (Yes/No)

The dataset contains clinical and demographic characteristics of patients diagnosed with differentiated thyroid cancer.

---

## Methodology

The overall workflow is:

```text
Dataset
   ↓
Data Preprocessing
   ↓
Feature Selection using FSRO
   ↓
Selected Features
   ↓
Machine Learning Models
   ↓
Deep Tabular Models
   ↓
Stacking Ensemble
   ↓
Model Evaluation
   ↓
Explainable AI

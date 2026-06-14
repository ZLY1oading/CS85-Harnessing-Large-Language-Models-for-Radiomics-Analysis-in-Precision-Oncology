# Harnessing Large Language Models for Radiomics Analysis in Precision Oncology
University of Sydney Capstone Project (GROUP-CS85, 2025S2)

A collaborative research project investigating the application of Large Language Models (LLMs) to radiomics prediction tasks and comparing their performance with traditional machine learning approaches.


## Overview
Radiomics extracts quantitative features from medical images to support clinically relevant tasks such as outcome prediction and treatment response assessment. However, downstream analysis remains challenging due to the high dimensionality and limited interpretability of radiomics data. This project investigates the application of Large Language Models (LLMs) to radiomics analysis by transforming structured radiomics features into textual representations.

Using 24 public radiomics datasets covering multiple cancer types, we established baseline models with traditional machine learning methods, including LDA, SVM, Random Forest, AdaBoost, and XGBoost, and compared them with LLM-based approaches using BERT and LLaMA. The study provides a comparative evaluation of traditional ML and LLM-based pipelines for radiomics prediction tasks.

## Objectives
- Establish baseline performance using traditional machine learning models;

- Transform structured radiomics features into textual representations for LLM-based analysis;

- Explore BERT- and LLaMA-based embedding approaches for downstream prediction tasks;

- Compare traditional ML and LLM-based pipelines across multiple radiomics datasets;

- Investigate the feasibility of applying large language models to radiomics analysis.

## Methodology
### Data Preparation

- Data cleaning and preprocessing;
- Train/validation/test splitting;
- Handling high-dimensional radiomics features.

### Traditional Machine Learning Models

Baseline models included:

- Linear Discriminant Analysis (LDA)
- Support Vector Machine (SVM)
- Random Forest (RF)
- AdaBoost
- XGBoost

### Feature Selection

Feature selection techniques included:

- LASSO
- Sequential Feature Selection (SFS)

### LLM-Based Approaches

Structured radiomics feature vectors were transformed into textual representations using a Feature-to-Text strategy.

Semantic embeddings were generated using:

- BERT
- LLaMA-3.1-8B

The generated embeddings were subsequently used for downstream classification tasks.

### Evaluation Metrics

Model performance was primarily evaluated using ROC-AUC, with additional metrics including:

- Accuracy
- Precision
- Recall
- F1-score

ROC curves, confusion matrices, and performance comparison tables were used to support model interpretation and comparison.

ROC-AUC was used as the primary evaluation metric, with accuracy, precision, recall, and F1-score reported as secondary metrics.

## Datasets
A total of **24 public radiomics datasets** were analysed in this study.

The datasets covered multiple cancer types and downstream prediction tasks, including survival prediction and treatment response classification.

Cancer types represented in the datasets include:

- Brain tumors

- Lung cancer

- Liver cancer

- Prostate cancer

- Kidney cancer

- Melanoma

- Head and neck cancer

- Soft tissue sarcomas

- Gastrointestinal stromal tumors (GISTs)

All datasets were obtained from the public repository provided by **RadiomicsHub (radiomics.uk)** and were used for research purposes only.

## Experimental Results

## Key Findings

## Repository Structure

## Team Contributions

## Project Materials

- Proposal

- Final Report

- Presentation Slides

## Acknowledgements

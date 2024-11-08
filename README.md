# Autism Spectrum Disorder Detection Using XAI

This project leverages machine learning and Explainable Artificial Intelligence (XAI) techniques to detect Autism Spectrum Disorder (ASD) image data. By prioritizing transparency and interpretability, the models aim to empower clinicians with actionable insights, enhancing diagnostic accuracy and consistency.

[Download The dataset Here](https://drive.google.com/drive/folders/1xDc_AgkMXEJ2vIhiduWB-6jg5CW3iaw8?usp=sharing)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dependincies](#dependencies)


## Introduction
Autism Spectrum Disorder (ASD) is a neurodevelopmental condition characterized by challenges in social interaction, communication, and behavior. This project applies machine learning models like SVM, Logistic Regression, and Random Forest and deep learning (using pre-trained models such as ResNet50) to predict ASD. Additionally, XAI techniques such as SHAP and LIME enhance the interpretability of the models.

## Features
- **Multi-Model Approach**: Combines tabular and image data for ASD detection.
- **Explainable AI**: Provides interpretability using SHAP, LIME, and Explainable Boosting Machine (EBM).
- **High Accuracy**: Demonstrates promising accuracy in ASD prediction.
- **Open-Source Dataset**: Utilizes ASD datasets from the UCI Machine Learning Repository.


## Prerequisites

Ensure you have the following installed on your system:
- Python 3.8 or higher
- pip (Python package installer)

## Setup Instructions

### 1. Clone the Repository
First, clone the repository to your local machine:
```bash

# go inside the repo then run the commands
#create virtual environment
python3 -m venv .venv
#for windows
.venv\Scripts\activate
pip install -r requirements.txt
```

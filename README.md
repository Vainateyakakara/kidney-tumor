# Kidney Tumor Classification using VGG16

## Overview
This project detects kidney tumors from CT scan images using a VGG16-based Convolutional Neural Network. The project follows an end-to-end MLOps workflow with data versioning, experiment tracking, and a modular machine learning pipeline.

## Features
- Kidney tumor classification from CT scans
- Transfer learning using VGG16
- Data ingestion and preprocessing pipeline
- Model training and evaluation
- Experiment tracking with MLflow and DagsHub
- Data and model versioning using DVC
- Flask-based testing and validation
- Reproducible ML workflow

## Tech Stack
- Python
- TensorFlow
- Keras (VGG16)
- MLflow
- DVC
- DagsHub
- Flask
- NumPy
- Git & GitHub


## Workflow
1. Data Ingestion
2. Data Validation
3. Data Transformation
4. Model Training
5. Model Evaluation
6. Experiment Tracking
7. Flask Application Testing

## Results
The model was trained using transfer learning with VGG16 and tracked using MLflow and DVC to ensure reproducibility and efficient experiment management.

## Installation

```bash
git clone <repository-url>
cd <repository-name>
pip install -r requirements.txt

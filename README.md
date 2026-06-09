<<<<<<< HEAD
# kidney-tumor

# Kidney-Disease-Classification-MLflow-DVC


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?
### STEPS:

Clone the repository. 

```bash
https://github.com/skrithik/kidney-tumor
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```

### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)



=======
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
>>>>>>> 7e58eed7ad74ecde3c3c002a48b33e3073545e8e

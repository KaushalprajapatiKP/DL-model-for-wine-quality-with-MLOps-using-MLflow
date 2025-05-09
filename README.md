# DL-model-for-wine-quality-with-MLOps-using-MLflow

This project builds a Deep Learning (ANN) model to predict wine quality using various physicochemical features. It leverages MLflow for experiment tracking, model logging, and reproducibility within an MLOps workflow.

## 🔧 Setup Instructions

### 1. Create a Virtual Environment

Create a conda virtual environment with Python 3.12:

conda create -n wine-mlflow-env python=3.12
conda activate wine-mlflow-env

### 2. Install Dependencies

Install required packages using:

pip install -r requirements.txt

### 3. Project Directory

Navigate to the research folder:

cd 1- folder

### 4. Launch MLflow UI

Run the MLflow tracking server:

mlflow ui

The MLflow UI will be available at: http://localhost:5000

### 5. Run the Research Notebook

Open and execute all cells in project-research.ipynb to:

## Load data

## Train and evaluate the ANN model

## Log experiments and metrics using MLflow

## 📊 Output

Model performance, metrics, and artifacts are logged and viewable via the MLflow UI.


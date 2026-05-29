# Guidewire Trajectory Prediction using LSTM

## Overview

This project explores trajectory prediction for endovascular guidewire navigation using Long Short-Term Memory (LSTM) networks.

The objective is to predict future guidewire tip positions from historical trajectory data extracted from the Guide3D dataset. The work was completed as part of my Final Year Project in Computer Science.

## Features

* Trajectory extraction from Guide3D annotations
* Data preprocessing and normalization
* Sliding-window sequence generation
* LSTM-based trajectory prediction
* Multi-step prediction experiments
* Custom loss function incorporating Final Displacement Error (FDE)
* Model evaluation using MSE, ADE, and FDE metrics

## Technologies

* Python
* PyTorch
* NumPy
* Scikit-learn
* Matplotlib
* Google Colab

## Dataset

This project uses the Guide3D dataset.

The dataset is not included in this repository due to licensing and academic-use restrictions.

Please obtain the dataset from the original source before running the notebook.

## Repository Structure

```text
Trajectory_prediction.ipynb   Main training and evaluation notebook
requirements.txt             Python dependencies
sample_results/              Example outputs and visualizations
```

## Running the Project

Install dependencies:

```bash
pip install -r requirements.txt
```

Open and run:

```bash
Trajectory_prediction.ipynb
```

using Jupyter Notebook or Google Colab.

## Notes

This repository represents the implementation and experimentation component of my undergraduate Final Year Project.

The project focuses on trajectory prediction and sequence modeling rather than deployment into a clinical environment.

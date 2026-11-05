# AI-Based Clinical Deterioration Prediction System

A research/educational project exploring clinical deterioration prediction using structured physiological measurements, sequential models, and clinical-language-model methods. The repository currently contains three Jupyter notebooks:

- [`DL_Assignment.ipynb`](DL_Assignment.ipynb)
- [`dl_assignment.ipynb`](dl_assignment.ipynb)
- [`Copy_of_DL_Assignment.ipynb`](Copy_of_DL_Assignment.ipynb)

> **Important:** This project is for learning and research only. It is not a medical device, has not been validated for clinical use, and must not be used to diagnose patients or guide treatment.

## Project approaches

The project explores the following techniques (see the notebooks for the actual implementation and results):

- Feed-forward deep neural networks for structured features
- LSTM, GRU, and bidirectional LSTM approaches for sequential data
- Bio_ClinicalBERT for clinical text
- Class-imbalance handling, including SMOTE where appropriate
- Evaluation using classification metrics and visualizations

The notebooks are coursework/experimentation artifacts and may not all contain identical or complete implementations. Treat their code and reported metrics as experimental results, not clinical evidence.

## Getting started

1. Clone this repository and open it in Jupyter Notebook, JupyterLab, or Google Colab.
2. Open a notebook and review its first cells for the dataset location and package imports.
3. Install only the dependencies required by the notebook you intend to run.
4. Configure the dataset path for your environment, then run cells in order.

The repository does not currently include a unified Python package, application entry point, dependency lockfile, or dataset. Dataset access and notebook-specific setup may therefore need to be configured separately. Do not commit patient data, credentials, or other sensitive information to this repository.

## Data, privacy, and responsible use

Clinical and physiological data can contain sensitive personal information. Use only data you are authorized to access, follow the dataset's license and applicable privacy rules, and avoid storing identifiable data in notebooks or their outputs. Before sharing notebooks, inspect them for private paths, credentials, and sensitive output cells.

Model performance can vary across populations, clinical settings, and data collection practices. Accuracy alone is not sufficient to assess a clinical prediction system; assess class-specific performance, calibration, data leakage, and external validity before making any research claims.

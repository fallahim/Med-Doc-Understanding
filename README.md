# Medical Document Understanding Repository

## Overview

This repository hosts a collection of tools and models for medical document understanding. It includes an Optical Character Recognition (OCR) model for extracting text from medical documents, a Large Language Model (LLM) for analyzing the extracted text, and an API created using Gradio for easy access to the functionalities of the project.

## Features


- Optical Character Recognition (OCR) for extracting text from medical documents.
- Large Language Model (LLM) for analyzing the extracted text.
- Gradio API for interacting with the models and tools.

## Directory Structure
```
├── data/ # Directory for storing sample medical documents
│ ├── example_doc1.pdf # Sample medical document 1
│ ├── example_doc2.pdf # Sample medical document 2
│ └── ...
├── models/ # Directory for storing trained models
│ ├── ocr_model/ # Optical Character Recognition model files
│ │ ├── ...
│ └── llm_model/ # Large Language Model files
│ ├── ...
├── notebooks/ # Jupyter notebooks for experimentation and training
│ ├── data_exploration.ipynb # Notebook for exploring the dataset
│ ├── ocr_training.ipynb # Notebook for training the OCR model
│ ├── llm_training.ipynb # Notebook for training the Large Language Model
│ └── ...
├── src/ # Source code for the project
│ ├── ocr.py # Implementation of the OCR model
│ ├── llm.py # Implementation of the Large Language Model
│ ├── api.py # Implementation of the Gradio API
│ └── ...
├── requirements.txt # Python dependencies required for the project
├── README.md # Project documentation
└── LICENSE # License information
```

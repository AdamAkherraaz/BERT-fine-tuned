# BERT Fine-Tuned for Emotion Classification

This project fine-tunes a BERT-based model (XLM-Roberta) for emotion classification on short texts or tweets. The pipeline includes data preprocessing, tokenization, model training, and performance evaluation.

## Table of Contents
- [Description](#description)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)


---

## Description

This project leverages the `XLM-Roberta` model to classify emotions in text. The main steps include:
1. Data cleaning and exploration.
2. Preparing data for training.
3. Fine-tuning the `XLM-Roberta` model on a labeled dataset.
4. Evaluating the model's performance.

---

## Prerequisites

- Python 3.12 or later
- GPU with CUDA support (optional but recommended for training)
- Python libraries:
  - `transformers`
  - `torch`
  - `datasets`
  - `scikit-learn`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/BERT-fine-tuned.git
   cd BERT-fine-tuned

## Create and activate a virtual environment:

  python3 -m venv venv
  source venv/bin/activate

## Install the required dependencies:
  pip install -r requirements.txt

## Usage

  1. Prepare the Dataset
      
    - Place your dataset in a CSV file named dataset.csv in the root directory.
    - The file should contain two main columns:
        - text: The text to classify.
        - label: The associated label (e.g., 0 = negative, 1 = neutral, 2 = positive).

  2. Train the Model

      - Open and run the NPL_emotions_classification.ipynb notebook to fine-tune the model.

  3. Evaluate the Model
      - The notebook includes evaluation metrics such as accuracy, precision, recall, and F1-score.

## Project Structure

└── BERT-fine-tuned
  ├── data_cleaning.ipynb
    ├── dataset.csv
    ├── NPL_emotions_classification.ipynb
    └── README.md

## Results

The fine-tuned model achieves the following metrics on the test set:

  Accuracy: 90%
  Precision: 88%
  Recall: 89%
  F1-Score: 88.5%


Made by Adam Akherraz
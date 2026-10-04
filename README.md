# IT Service Desk Ticket Classification Using Machine Learning and Deep Learning

## Overview

This project investigates the classification of IT service desk tickets using and comparing traditional machine learning, recurrent neural networks, and transformer-based models.

The study follows the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** methodology and evaluates model performance using both balanced and imbalanced datasets.

## Models Evaluated

Six models were evaluated across three categories:

### Traditional Machine Learning

* Support Vector Machine (SVM)
* Naïve Bayes

### Recurrent Neural Networks

* Long Short-Term Memory (LSTM)
* Bidirectional Long Short-Term Memory (BiLSTM)

### Transformer-Based Models

* BERT
* DistilBERT

## Dataset

The project uses text-based **IT service desk ticket data** for classification.

The dataset contains **47,837 ticket records** across the relevant ticket categories.

The original dataset is not included in this repository where redistribution is not permitted.

## Methodology

The project follows the six phases of CRISP-DM:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modelling
5. Evaluation
6. Deployment

The experiments were conducted using **Google Colab**.

## Data Processing and Exploratory Data Analysis

The data preparation and exploratory analysis included:

* Checking for missing values
* Examining the distribution of ticket classes
* Analysing ticket/text length
* Identifying short and long text entries
* Generating word clouds to examine frequently occurring terms
* Preparing the text data for model training
* Investigating both balanced and imbalanced datasets

## Model Comparison

The models were evaluated and compared based on their classification performance.

| Model      | Accuracy |
| ---------- | -------: |
| BERT       |      91% |
| DistilBERT |      90% |
| BiLSTM     |      89% |
| LSTM       |      88% |

Additional results for SVM and Naïve Bayes are presented in the Jupyter Notebook.

## Technologies

* Python
* Natural Language Processing (NLP)
* Scikit-learn
* TensorFlow / Keras
* Google Colab
* BERT
* DistilBERT

## Project Structure

```text
IT-Service-Desk-Ticket-Classification/
│
├── IT-Service-Desk-Ticket-Classification.ipynb
├── README.md
└── results/
```

## Key Finding

Among the evaluated models, **BERT achieved the highest classification accuracy at 91%**, followed by DistilBERT at 90%.

The project demonstrates the differences in classification performance between traditional machine learning approaches, recurrent neural networks, and transformer-based NLP models.

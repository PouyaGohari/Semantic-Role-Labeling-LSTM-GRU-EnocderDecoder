# Semantic-Role-Labeling-LSTM-GRU-EnocderDecoder
This repository contains the implementation and analysis of Semantic Role Labeling (SRL) using three different models: LSTM Encoder, GRU Encoder, and an Encoder-Decoder model. The project is part of the third computer assignment for the Natural Language Processing course at the University of Tehran.

## Table of Contents

- [Introduction](#introduction)
- [Assignment Overview](#assignment-overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Results and Analysis](#results-and-analysis)
- [Report](#report)
- [License](#license)

## Introduction

Semantic Role Labeling (SRL) is a process in Natural Language Processing (NLP) that involves determining the roles that words play in a sentence. This project implements SRL using three different models: LSTM Encoder, GRU Encoder, and an Encoder-Decoder model. Additionally, the project explores using a question-answering approach with beam search for solving the SRL problem.


## Assignment Overview

**Dataset:** The dataset used for training is uploaded [here](data).

### Model 1: LSTM Encoder Model

- Implement an LSTM-based encoder model for Semantic Role Labeling.
- Train the model on an SRL dataset.
- Analyze the model's performance.

### Model 2: GRU Encoder Model

- Implement a GRU-based encoder model for Semantic Role Labeling.
- Train the model on an SRL dataset.
- Compare its performance with the LSTM model.

### Model 3: Encoder-Decoder Model with Beam Search and Attention Mechanism

- Implement an Encoder-Decoder model for SRL, using a question-answering method.
- Apply beam search to enhance the decoding process.
- Evaluate and compare the results with the other two models.

### Analysis

- Analyze and compare the performance of all three models on the SRL task.
- Discuss the strengths and weaknesses of each approach.

## Prerequisites

Before you begin, ensure you have the following requirements:

- Libraries: `torch`,  `matplotlib`, `scikit-learn`
- Basic understanding of NLP concepts, especially SRL, LSTM, GRU, and Encoder-Decoder architectures.


## Installation

To clone and run this repository locally:
```sh
git clone https://github.com/PouyaGohari/Semantic-Role-Labeling-LSTM-GRU-EnocderDecoder.git
cd Semantic-Role-Labeling-LSTM-GRU-EnocderDecoder
```

## Usage

This project is implemented in a single Jupyter notebook:

- **Notebook:** [`CA3.ipynb`](CA3.ipynb)

The notebook is self-contained, with detailed instructions and code explanations for all models.

## Results and Analysis

- **LSTM Encoder Model:** Results and analysis of the LSTM model for SRL.
- **GRU Encoder Model:** Comparison with the LSTM model and discussion of differences.
- **Encoder-Decoder Model:** Evaluation of the model's performance using beam search and attention mechanism, with a comparison to the other models

## Report

A comprehensive report detailing the methodology, implementation, results, and analysis for each model is available [here](My%20Report/Report.pdf).

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

# Assignment 02 - Deep Learning Applications

This project was completed as part of **Deep Learning coursework** at the **University at Buffalo**. It brings together multiple advanced deep learning applications across anomaly detection, transformer-based text classification, and large language model fine-tuning for summarization.

## Type
Individual project

## Project Overview

This assignment includes:
- a written theory component
- an autoencoder-based anomaly detection pipeline
- a Transformer model implemented from scratch in PyTorch
- fine-tuning of a pretrained BART model for abstractive summarization
- bonus work on linear probing with encoder LLMs and summarization on an additional dataset

## My Work

### Part 2 - Autoencoder for Anomaly Detection
Built an anomaly detection pipeline using a PyTorch autoencoder on time-series data. The workflow includes preprocessing, scaling, reconstruction-based anomaly scoring, and evaluation using classification metrics.

### Part 3 - Transformer from Scratch for Text Classification
Implemented a Transformer architecture from scratch in PyTorch for AG News classification, including tokenization, vocabulary building, positional encoding, self-attention, encoder blocks, and end-to-end training/evaluation.

### Part 4 - Abstractive Summarization with BART
Fine-tuned `facebook/bart-base` for abstractive summarization on the BillSum dataset using Hugging Face tooling and evaluated the model with ROUGE, BLEU, and BERTScore.

### Bonus - Encoder LLM Linear Probing
Used a frozen pretrained encoder model with a lightweight classifier head for spam detection on the Enron Spam dataset.

### Bonus - Summarization Extension
Extended the summarization pipeline to a second dataset, Multi-News, to compare generalization and summarization quality.

## Project Structure

```text
assignment-02-deep-learning-applications/
├── README.md
├── notebooks/
│   ├── 02_autoencoder_anomaly_detection.ipynb
│   ├── 03_transformer_from_scratch_text_classification.ipynb
│   ├── 04_bart_summarization_finetuning.ipynb
│   ├── 05_bonus_llm_spam_classification_linear_probing.ipynb
│   └── 06_bonus_multinews_summarization.ipynb
├── reports/
│   └── 01_part1_theory_answers.pdf
└── metadata/
    ├── datasets.txt
    └── weights.txt
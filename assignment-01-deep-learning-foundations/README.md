# Assignment 01 - Sequence Modeling with LSTMs

This project was completed as part of **Deep Learning coursework** at the **University at Buffalo**. The assignment covers sequence modeling across two different problem settings: **time-series forecasting** and **sentiment analysis**, using recurrent neural networks and LSTM-based architectures.

Originally completed as a team coursework assignment, this project has been cleaned, reorganized, and documented for portfolio presentation on GitHub.

## Collaboration and Contribution

This was a **team-based coursework project**.

**My primary contributions were Part 3 and Part 4**, where I implemented and evaluated sequence modeling pipelines for:
- **time-series forecasting using stacked LSTMs**
- **sentiment analysis using baseline and improved LSTM architectures**

These sections best reflect my work on deep learning model development, training workflows, hyperparameter experimentation, and performance analysis.

## My Work

### Part 3 - Time-Series Forecasting with LSTMs
Built a deep learning pipeline for forecasting household electric power consumption using recurrent neural networks.

Key work included:
- preprocessing a large real-world electricity consumption dataset
- handling missing values and feature scaling
- exploring temporal patterns through visualizations
- generating sequence windows for supervised forecasting
- implementing a **stacked LSTM model** in PyTorch
- performing **hyperparameter search** across learning rate and batch size
- applying **early stopping**
- evaluating performance using **MAE, RMSE, and R²**

### Part 4 - Sentiment Analysis with LSTMs
Developed and compared LSTM-based models for multi-class sentiment analysis on airline tweet data.

Key work included:
- preprocessing and analyzing tweet text data
- handling missing values and preparing stratified train/validation/test splits
- tokenization and vocabulary preparation
- implementing a **baseline stacked LSTM classifier**
- training and evaluating with accuracy, precision, recall, F1-score, and confusion matrix analysis
- building an **improved LSTM architecture** with:
  - bidirectional LSTM layers
  - attention mechanism
  - layer normalization
  - dropout regularization
- comparing baseline vs improved model behavior and performance

## Project Structure

```text
assignment-01-deep-learning-foundations/
├── README.md
├── notebooks/
│   ├── 01_part1.ipynb
│   ├── 02_part2.ipynb
│   ├── 03_part3_time_series_forecasting_lstm.ipynb
│   └── 04_part4_sentiment_analysis_lstm.ipynb
├── reports/
│   └── assignment_01_report.pdf
└── metadata/
    ├── weights.txt
    └── datasets.txt
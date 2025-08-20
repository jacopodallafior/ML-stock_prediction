# Stock Market Prediction with Transformer and LSTM Models

This repository contains a Jupyter Notebook and supporting material for a research project comparing **Transformer** and **Long Short-Term Memory (LSTM)** models for stock market prediction. The project focuses on predicting the historical stock prices of **Apple (AAPL)** and **Microsoft (MSFT)** using machine learning techniques.

---

## 📄 Project Overview

Stock market forecasting is a complex challenge due to the **nonlinear, volatile, and stochastic** nature of financial data. In this work, we compare the performance of two state-of-the-art deep learning architectures:

- **LSTM (Long Short-Term Memory)**  
  Well-suited for sequential data, capable of capturing long-term temporal dependencies.

- **Transformer**  
  Based on attention mechanisms, excels at capturing global dependencies and parallel training.

The models are evaluated on their ability to predict stock closing prices and are compared using the metrics:  
- **Root Mean Square Error (RMSE)**  
- **Mean Absolute Percentage Error (MAPE)**  

Results show that **LSTM outperforms Transformer under the tested conditions**, providing lower prediction error on both AAPL and MSFT data.

---

## 📂 Repository Structure

- **`Transformers_model_01.ipynb`**  
  Jupyter Notebook implementing the LSTM and Transformer models. Includes:
  - Data preprocessing
  - Model design
  - Training and hyperparameter tuning
  - Evaluation and visualization of results

- **`FINAL_PAPER.pdf`**  
  The **final research report** presenting the complete methodology, experiments, results, and discussion.  
  👉 [Read the full paper here](FINALPAPER.pdf)

- **`requirements.txt`**  
  Python dependencies needed to run the notebook.

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Grandediw/stock-market-prediction.git
   cd stock-market-prediction

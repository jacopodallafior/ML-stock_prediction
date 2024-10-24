```markdown
# Stock Market Prediction with LSTM and Transformer Models

This repository contains the code and methodology for comparing Long Short-Term Memory (LSTM) networks and Transformer-based models in predicting stock prices. The goal of this project is to enhance stock market forecasting by evaluating these machine learning models on historical stock data.

## Project Structure

The project is organized as follows:

```
- src/
  - lstm_model.py
  - transformer_model.py

- README.md
- requirements.txt
- data/
  - stock_data.csv
```

### 1. `src/`
This folder contains all the Python scripts for the project:
- **`data_preprocessing.py`**: Script for data collection, cleaning, and preprocessing of stock data.
- **`lstm_model.py`**: LSTM model architecture for stock price forecasting.
- **`transformer_model.py`**: Transformer model architecture adapted for time series forecasting.
- **`train.py`**: Script for training both LSTM and Transformer models.
- **`evaluation.py`**: Script for evaluating models using RMSE and MAPE.

### 2. `data/`
This folder contains the dataset used in the project:
- **`stock_data.csv`**: Historical stock data for Apple (AAPL) and Microsoft (MSFT), retrieved using the yfinance library.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-market-prediction.git
   cd stock-market-prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the stock data:
   - Run the `data_preprocessing.py` script to fetch the latest stock data from Yahoo Finance.

## Usage

1. **Preprocessing**:
   Run the `data_preprocessing.py` script to clean and preprocess the stock data.
   ```bash
   python src/data_preprocessing.py
   ```

2. **Training the Models**:
   - To train the LSTM model:
     ```bash
     python src/train.py --model lstm
     ```
   - To train the Transformer model:
     ```bash
     python src/train.py --model transformer
     ```

3. **Evaluation**:
   After training, you can evaluate the models on test data:
   ```bash
   python src/evaluation.py --model lstm
   python src/evaluation.py --model transformer
   ```

## Results

The project compares the LSTM and Transformer models in predicting stock prices. Performance is evaluated using two metrics:
- **Root Mean Square Error (RMSE)**
- **Mean Absolute Percentage Error (MAPE)**

The project includes visualizations of predicted vs actual stock prices to help understand model performance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- Stefano Tonini
- Jacopo Dallafior
```

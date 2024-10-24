
# Stock Market Prediction with Transformer and LSTM Models

This repository contains a Jupyter Notebook that implements and compares Transformer and Long Short-Term Memory (LSTM) models for stock market prediction, focusing on the historical stock prices of Apple (AAPL) and Microsoft (MSFT).

## Project Structure

The repository contains the following files:

- **`Transformers_model_01.ipynb`**: A Jupyter Notebook that implements the machine learning models (LSTM and Transformer) for stock market forecasting, including data preprocessing, model training, and evaluation.
- **`First_draft___Research_Methodology.pdf`**: A draft research report outlining the methodology, objectives, and initial findings for the project, including comparisons between the LSTM and Transformer models for stock price forecasting.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Grandediw/stock-market-prediction.git
   cd stock-market-prediction
   ```

2. Install the necessary dependencies:
   - Ensure you have Jupyter Notebook installed and use the following command to install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Transformers_model_01.ipynb
   ```

## Usage

1. **Data Preprocessing**:
   The notebook begins by collecting and preprocessing stock price data from Yahoo Finance using the `yfinance` library.
   
2. **Model Training**:
   The notebook includes code to train both LSTM and Transformer models. Adjust the hyperparameters as necessary to optimize performance.
   
3. **Evaluation**:
   The models are evaluated using key metrics such as Root Mean Square Error (RMSE) and Mean Absolute Percentage Error (MAPE).

## Results

The notebook provides a detailed comparison between the LSTM and Transformer models, displaying the prediction performance on historical stock data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- Stefano Tonini
- Jacopo Dallafior
```

You can copy and paste this directly into your repository's `README.md` file. Let me know if you need any more adjustments!

# Stock Market Prediction

This repository contains a Jupyter notebook for stock market prediction and time-series analysis.

## Project Overview

The notebook [stock_market_prediction.ipynb](stock_market_prediction.ipynb) loads historical stock data from `stockprediction.csv`, performs data exploration and preprocessing, and builds a neural-network-based forecasting model using TensorFlow/Keras. It then visualizes predictions across training, validation, test, and recursive forecast windows.

## Requirements

- Python 3.9 or newer
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- matplotlib
- tensorflow

## How to Run

1. Open the notebook in Jupyter Notebook, JupyterLab, or VS Code.
2. Make sure `stockprediction.csv` is available in the same folder as the notebook.
3. Install the required packages if needed:

```bash
pip install pandas numpy matplotlib tensorflow jupyter
```

4. Run the cells in [stock_market_prediction.ipynb](stock_market_prediction.ipynb) from top to bottom.

## Notes

- The notebook includes data visualization and model evaluation plots.
- If you want to reuse the project with a different dataset, update the CSV path in the notebook and adjust the preprocessing steps accordingly.

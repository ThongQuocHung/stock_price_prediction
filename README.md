# Stock Price Prediction using RNN

## Overview
This project aims to predict stock prices using deep learning models, specifically Recurrent Neural Networks (RNNs). The dataset consists of historical stock prices, and the model is trained to forecast future prices based on past trends.

## Features
- Data preprocessing including feature selection and scaling
- Implementation of RNN for stock price prediction
- Training and testing of the model
- Visualization of predicted vs actual prices

## Installation
1. Clone the repository:
   ```sh
   git clone <repository_url>
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

## Dataset
The project uses a historical stock price dataset (`BABA.csv`). The dataset includes features such as:
- Open price
- High price
- Low price
- Close price
- Adjusted Close price
- Volume

## Model Training
1. Load and preprocess the data
2. Apply feature selection using `SelectKBest`
3. Normalize the data using `MinMaxScaler`
4. Create training and testing datasets
5. Train the model using RNN (LSTM architecture)
6. Evaluate the model and visualize the results

## Results
- The model predicts stock price movements based on historical trends.
- Visualization helps in understanding model accuracy.

## Usage
To use the model for predictions:
```python
python predict.py --input stock_data.csv
```

## Contributors
- [Quoc Hung]

## License
This project is licensed under the MIT License.



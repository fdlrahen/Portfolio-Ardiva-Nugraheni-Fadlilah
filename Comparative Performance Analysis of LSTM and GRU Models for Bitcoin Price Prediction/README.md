# 📈 Bitcoin Price Prediction App with LSTM & GRU

A Streamlit-powered web application that forecasts Bitcoin closing prices using deep learning techniques—Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) models. Users can interactively train models, tweak parameters, and visualize predictions against actual price data.

## 🚀 Features

- Load and preprocess historical Bitcoin data
- Train LSTM and GRU models on time series data
- Evaluate models using Mean Absolute Error (MAE)
- Visual comparison between predicted and actual closing prices
- Returns comparison visualization
- Display model architecture and details

## 📊 Dataset

The app uses historical Bitcoin data from this public CSV

## 🛠 Technologies Used

- Streamlit
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Keras (TensorFlow backend)

## ⚙️ Parameters (Set via Sidebar)

- `Test Size` (0.05 – 0.3)  
- `Window Length` (5 – 30 days)  
- `LSTM Neurons` / `GRU Neurons` (10 – 100)  
- `Dropout Rate` (0.1 – 0.5)  
- `Epochs` (10 – 200)  
- `Batch Size` (1 – 32)  
- `Loss Function`: `mae` or `mse`  
- `Optimizer`: `adam` or `rmsprop`  

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd bitcoin-predictor

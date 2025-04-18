# -Time-Series-Forecasting-with-Echo-State-Networks-


## 📌 Overview
This project demonstrates time series forecasting using Echo State Networks (ESNs), a type of recurrent neural network optimized for sequence learning with minimal training overhead.

## 🧩 Components Used
- Echo State Network (Reservoir Computing)
- Python
- Numpy, Matplotlib, Scikit-learn
- Optionally: pyESN library

## 🌟 Features
- Lightweight & efficient RNN model
- Captures non-linear temporal dependencies
- Requires training only the output weights
- Performs well with noisy data

## ⚙️ Methodology
1. Preprocess time series data
2. Initialize ESN (random input/reservoir weights)
3. Train only output weights
4. Forecast future values
5. Evaluate with metrics (RMSE, MAE)

## 🔧 Usage
```bash
# Install dependencies
pip install numpy matplotlib scikit-learn

# Run ESN (example file)
python train_esn.py

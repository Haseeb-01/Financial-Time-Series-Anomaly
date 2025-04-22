
# 📈 Stock Market Anomaly Detection with Yahoo Finance Data 🔍💰

Welcome to the **Stock Market Anomaly Detection** project!  
This tool analyzes historical stock price data from Yahoo Finance to detect anomalies and potential market manipulations using unsupervised learning and time-series forecasting.  
Built with ❤️ in **Google Colab**, it leverages **Isolation Forest**, **LSTM**, and **visualizations** to uncover unusual trends. 🚀📊

---

## 🌟 Project Overview

This project processes stock price data for selected companies, calculates financial indicators, detects anomalies using unsupervised methods and forecasting, and visualizes the results. It’s designed to identify irregularities in stock price trends that might suggest market manipulations.

### ✨ Key Features
- 📥 **Data Preprocessing**: Handles historical stock data for multiple companies.
- 📈 **Financial Indicators**: Calculates SMA, EMA, RSI, and Bollinger Bands.
- 🧠 **Anomaly Detection**: Uses Isolation Forest & LSTM.
- 📊 **Visualizations**: Graphs with anomalies + correlation heatmaps.

---

## 📂 Repository Structure

```bash
📁 model_outputs/               # Contains anomaly plots & saved models
📄 correlation_heatmap_aapl.png # Correlation heatmap of AAPL indicators
📄 msft_anomaly_graph.png       # MSFT anomaly plot
```

⚠️ **Note**: The dataset (`stock_details_5_years.csv`) is hosted on Google Drive due to size constraints.

---

## 🚀 How to Run the Project

### ▶️ Run in Google Colab

1. Open in Colab ➡️ [🚀 Click to Open](https://colab.research.google.com/drive/1ZuIMyfFQnUAPL3XqnHBz5a-pwEtLC9Y3?usp=sharing)
2. Mount Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
3. Ensure the dataset is located at `/content/drive/MyDrive/stock_details_5_years.csv`
4. Run cells to:
   - 📦 Preprocess data
   - 🧮 Calculate indicators
   - 🧠 Detect anomalies
   - 📈 Plot graphs & heatmaps
5. 🖼️ Download results like `company_anomaly_graph.png`

---

## 🛠️ Steps Completed

1. ✅ **Preprocessing**
2. 🧠 **Financial Indicators**
3. 🔎 **Isolation Forest (Unsupervised)**
4. 🔮 **LSTM Forecasting**
5. 🖼️ **Visualizations**

---

## 📊 Example Output

- 🟦 Blue: Price trend  
- 🔴 Red: Isolation Forest anomalies  
- 🟢 Green: LSTM anomalies  
- 🔥 Heatmaps: Indicator correlations

---

## 🧰 Prerequisites

- 🗃️ Dataset: `stock_details_5_years.csv`  
- 📦 Libraries:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`
  - `tensorflow`
  - `google-colab`

---

## 🚧 Future Enhancements

- ➕ Add more indicators (MACD, Stochastic)
- 🧪 Try DBSCAN
- 📅 Use Prophet for time series
- 🌐 Build a Streamlit Dashboard

---

## 💖 Credits

Made with 💻 + ☕ by **[Haseeb Cheema](https://github.com/Haseeb-01)**  
🙏 Special thanks to the open-source community!

---

## ⭐ Support This Project

If you find this project useful, please give it a ⭐ on GitHub!  
It helps more people discover and benefit from it.

---

## 📜 License

📝 Licensed under the **MIT License**

---

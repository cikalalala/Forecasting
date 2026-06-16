# 🛣️ TrafficLSTM: Deep Learning Traffic Forecaster & Fleet Optimization Dashboard

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.x-red.svg)

**TrafficLSTM** is an advanced web dashboard powered by Deep Learning (Long Short-Term Memory networks). It is explicitly designed to forecast traffic volume on the I-94 Interstate highway by analyzing historical time-series data and simulating the impact of complex weather conditions (snow, rain, cloud cover, and temperature).

Beyond raw volume predictions, this system features a **B2B Fleet Logistics Calculator** that translates traffic delays into real-world financial metrics. This helps logistics companies and enterprise fleets optimize their departure schedules, avoid severe congestion, and minimize fuel waste.

## ✨ Key Enterprise Features
- **🧠 Deep Learning Core:** Built on a robust LSTM model to accurately capture sequential time-series traffic patterns.
- **🌤️ Dynamic Weather Simulation:** Real-time parameter tuning to simulate the impact of extreme weather, accidents, and roadwork.
- **🗺️ Live Heatmap Visualization:** Interactive 3D maps using PyDeck to visualize congestion density across highway segments.
- **🚚 Fleet Logistics Optimizer:** Calculates estimated financial losses (in IDR) and fuel waste for convoys trapped in traffic.
- **🤖 AI Chat Assistant:** A smart conversational interface that extracts insights directly from the AI's predictive state to guide user decisions.

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/cikalalala/Forecasting.git
   cd Forecasting
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Dashboard**
   ```bash
   streamlit run app.py
   ```

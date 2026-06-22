# Weather Prediction Using RNN

A Deep Learning-based time-series forecasting platform designed to predict weather conditions using Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) networks. 

---

## 🚀 Project Overview
Weather forecasting is inherently complex due to the dynamic and non-linear nature of meteorological data. Traditional machine learning models often fail to capture sequential dependencies. This project leverages **RNNs** and **LSTMs** to model temporal patterns from historical weather logs, delivering highly accurate predictions for parameters like temperature, humidity, and precipitation.

### Key Features
* **Sequential Modeling:** Utilizes deep learning layers optimized for time-series memory retention.
* **Robust Preprocessing:** Scaled feature inputs and implemented a sliding-window data structure.
* **Interactive Dashboard:** Combined an intuitive web frontend to display real-time predictions and historical trends seamlessly.

---

## 📊 Dataset & Preprocessing
The model is trained on historical meteorological records (e.g., the Seattle Weather Dataset). 
* **Feature Engineering:** Extracted relevant time-lagged variables.
* **Scaling:** Normalized data using `MinMaxScaler` to optimize gradient descent performance in deep layers.
* **Time Windows:** Transformed the dataset into a supervised learning format using historical time steps to predict future metrics.

---

## 🏗️ Model Architecture
The core deep learning network is constructed using TensorFlow/Keras:
1. **Input Layer:** Accepts shaped 3D time-series tensors.
2. **LSTM/RNN Layers:** Captures short and long-term temporal trends without suffering from the vanishing gradient problem.
3. **Dropout Layers:** Implemented to prevent overfitting during dense training epochs.
4. **Dense Output Layer:** A regression layer predicting final continuous meteorological metrics.

---

## 🛠️ Tech Stack
* **Backend & ML:** Python, TensorFlow, Keras, Scikit-Learn, Pandas, NumPy
* **Frontend/UI:** React / Streamlit
* **Environment:** Jupyter Notebooks / Python 3.x

---

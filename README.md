# 🔋 Electric Vehicle Battery Life Prediction Using ANN (Deep Learning)

A deep learning-based web application built with **Streamlit** that predicts the remaining battery life of electric vehicles (EVs) using Artificial Neural Networks (ANN). This tool is designed to support EV manufacturers, fleet managers, and researchers in estimating battery degradation and lifecycle based on real-world features.

---

## 🚀 Demo and 📊 Sample UI

<img width="945" alt="Screenshot 2025-06-16 at 11 24 18 PM" src="https://github.com/user-attachments/assets/c3d0aed8-1bff-4c64-8b40-064e02d5c968" />

---

## 📦 Features

- ✅ User-friendly Streamlit web interface
- ✅ Predict battery life from relevant input parameters
- ✅ Pre-trained ANN model (`battery_life_model.h5`)
- ✅ Preprocessing with `StandardScaler` and `LabelEncoder` (`.pkl` files)
- ✅ End-to-end deployment-ready

---

## 🧠 Model Overview

The core model is an **Artificial Neural Network** (ANN) trained on EV battery performance data. It uses features like:

- Vehicle age  
- Number of charge-discharge cycles  
- Average operating temperature  
- Usage patterns, etc.

The model outputs the **predicted battery life in percentage**.

---

## 🖥️ Tech Stack

| Layer            | Technology             |
|------------------|------------------------|
| Frontend UI      | Streamlit              |
| Model            | TensorFlow/Keras (ANN) |
| Preprocessing    | Scikit-learn           |
| Deployment-ready | Python Virtual Env     |

---

## 🛠️ Installation

Clone the repo and set up the environment:


git clone https://github.com/Anil-Katwal/Electric-Vehicle-Battery-Life-Prediction-Using-ANN-Deep-Learning-.git
cd Electric-Vehicle-Battery-Life-Prediction-Using-ANN-Deep-Learning-
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
______
## Run the app:
streamlit run app.py

## 📌 Future Improvements
🔄 Real-time data integration from EV sensors

☁️ Cloud-based deployment (Streamlit Cloud / AWS / GCP)

📈 Model tuning using LSTM or transformer architectures

🛡️ Add authentication for secure enterprise usage

## 🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## 📜 License
This project is licensed under the MIT License.
## 🙋‍♂️ Maintainer
Anil Katwal
📧 Email : Aniljungkatwal@gmail.com
```bash
## 📁 Project Structure
├── app.py                      # Streamlit app entry point
├── battery-life-prediction.ipynb  # Jupyter notebook for training & exploration
├── battery_life_model.h5       # Trained ANN model
├── scaler.pkl                  # StandardScaler for preprocessing
├── label_encoder.pkl           # LabelEncoder for categorical features
├── requirements.txt            # Python dependencies
└── README.md                   # You're here!

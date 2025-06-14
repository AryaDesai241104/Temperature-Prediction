# 🌡️ Temperature Prediction using LSTM & RNN

This project implements a deep learning-based temperature prediction system using historical weather data. It leverages both **Long Short-Term Memory (LSTM)** and **Simple Recurrent Neural Network (RNN)** models to forecast temperature values, and combines their predictions for improved accuracy.

---

## 📌 Key Features

- Uses historical hourly weather data (2006–2016)
- LSTM & Simple RNN models implemented from scratch
- Ensemble method for averaging predictions
- MAE as evaluation metric; ~98.5% sample prediction accuracy
- Final report, notebooks, and datasets organized by folder

---

## 📁 Folder Structure

Temperature-Prediction/
├── data/ ← Raw datasets (Excel)
├── notebooks/ ← Jupyter Notebooks for LSTM/RNN training
├── reports/ ← Final PDF report + HTML output
├── requirements.txt
├── README.md
└── LICENSE

yaml
Copy
Edit

---

## 🧪 Tech Stack

- Python 3.11
- TensorFlow
- Pandas
- NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🧰 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/AryaDesai241104/Temperature-Prediction.git
cd Temperature-Prediction

# Create environment and install dependencies
pip install -r requirements.txt

# Launch notebooks
jupyter notebook
📊 Sample Results
Model	MAE	Accuracy
LSTM	1.23°C	~98.4%
Simple RNN	1.35°C	~98.2%
Ensemble	1.18°C	~98.5%

📑 Report
Check the full report: reports/Temperature_Prediction_Final_Report.pdf

🙋‍♂️ Author
Arya Desai
Final Year BTech CSE
Date: May 2025

📜 License
This project is licensed under the MIT License.
```

# HVAC Anomaly Detection with Supervised Learning

This project applies supervised machine learning to detect anomalies in HVAC (Heating, Ventilation, and Air Conditioning) systems using real-time sensor data. It was developed as part of a practical exploration into time series classification and anomaly detection techniques.

---

## Why This Project

HVAC systems play a crucial role in environmental control, but anomalies such as mechanical faults or inefficient energy usage can go undetected without proper monitoring. Traditional threshold-based systems lack adaptability.

This project uses data-driven models to learn patterns of normal behavior and flag unusual deviations that may signal faults or inefficiencies.

---

## Key Components

| Component              | Description |
|------------------------|-------------|
| Sensor Data            | Includes temperature, humidity, airflow, and energy metrics |
| Feature Engineering    | Rolling means, standard deviation, lag features, and z-scores |
| Data Preprocessing     | Handling missing values, normalization, and noise smoothing |
| Supervised Models      | Logistic Regression, Random Forest, XGBoost for classification |

---

## Results

- Achieved high accuracy in flagging known anomalies  
- Time-windowed statistical features improved detection performance  
- Easily extendable to real-world industrial and commercial HVAC systems

---

## Repository Contents

- `main_notebook.ipynb` – Full workflow: data preparation, feature engineering, modeling
- `data/` – Sample HVAC datasets (simulated or anonymized)
- `requirements.txt` – Python dependencies used

---

## Dataset

- Simulated or real sensor logs from HVAC systems  
- Features: temperature, humidity, energy use, flow rate, timestamp  
- Labels: 0 = normal, 1 = anomaly
- Dataset available at:
https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

Developed as part of a practical project in anomaly detection and time series analysis.

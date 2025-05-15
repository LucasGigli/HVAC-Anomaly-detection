# HVAC Anomaly Detection with Z-Score Method

This project focuses on detecting anomalies in HVAC (Heating, Ventilation, and Air Conditioning) systems using statistical methods. It was developed as a practical implementation of anomaly detection for sensor-based time series data.

---

## Why This Project

HVAC systems are critical for regulating indoor environments. Malfunctions, inefficiencies, or sensor failures often go unnoticed until major breakdowns occur. Early anomaly detection can help optimize energy use, reduce costs, and prevent equipment damage.

This project uses a statistical approach based on the Z-score to flag abnormal behavior in sensor readings.

---

## Methodology

| Step                  | Description |
|------------------------|-------------|
| Data Source           | Simulated sensor readings from an HVAC unit |
| Feature Focus         | Temperature sensor time series |
| Anomaly Detection     | Z-score computed on rolling windows |
| Thresholding          | Observations with Z-scores beyond a set threshold are flagged as anomalies |

---

## Results

- Z-score effectively identified spikes and drops in sensor data
- Rolling mean and standard deviation helped smooth the data and enhance anomaly visibility
- Visualizations clearly showed detected anomalies over time

---

## Repository Contents

- `HVAC_Anomaly_Detection.ipynb` – Full workflow: data loading, processing, Z-score computation, and visualization
- `data/` – Contains the sample HVAC dataset used in the notebook
- `requirements.txt` – Required Python packages

---

## Dataset

- Simulated HVAC sensor log
- Feature: `Temperature` over time
- Labels: Not required (unsupervised anomaly detection)

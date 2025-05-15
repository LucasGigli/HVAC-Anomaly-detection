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

## Repository Contents

- `HVAC_Anomaly_Detection.ipynb` – Full workflow: data loading, processing, Z-score computation, and visualization
- `data/` – Contains the sample HVAC dataset used in the notebook

---

## Dataset

- Simulated HVAC sensor log
- Feature: `Temperature` over time
Dataset available at: https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

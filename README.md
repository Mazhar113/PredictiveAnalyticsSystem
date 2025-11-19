# PredictiveAnalyticsSystem

[![Python](https://img.shields.io/badge/python-3.11-blue)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.109.2-green)](https://fastapi.tiangolo.com/)
[![License](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)

## Overview
**PredictiveAnalyticsSystem** is a fully interactive AI dashboard for real-time predictions, anomaly detection, and model management.  
It supports:

- Live predictions with neural networks
- Automatic retraining when new CSV data is uploaded
- Outlier detection and highlighting in prediction graphs
- Interactive tooltips showing feature values
- Model versioning with rollback capability
- Automatic live refresh every few seconds
- Anomaly summary statistics (count of outliers, average prediction, best model MAE)
- Real-time notifications via dashboard banner, email, and SMS

This system is designed for proactive monitoring and analytics in AI-driven workflows.

---

## Features

| Feature | Description |
|---------|-------------|
| Live Predictions | Input feature values and receive instant predictions |
| Prediction History Graph | Interactive, with outlier highlighting and tooltips |
| Model Versioning | Keep track of previous models with rollback capability |
| Automatic Retraining | Upload new CSV data to retrain the model seamlessly |
| Anomaly Summary | Outlier count, average prediction, and best model MAE |
| Notifications | Red banner alerts on dashboard; optional Email/SMS alerts |
| Live Refresh | Dashboard updates automatically every few seconds |

---

## Installation

1. **Clone the repository**
```bash
git clone https://github.com/Mazhar113/PredictiveAnalyticsSystem.git
cd PredictiveAnalyticsSystem

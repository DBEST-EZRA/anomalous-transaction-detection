# Real-Time Anomaly Detection System

This project implements a real-time anomaly detection system to monitor user transactions. Each user has an independent model trained dynamically on their first 20 transactions. After training, the system predicts whether new transactions are anomalous or normal.

## Features

- **Real-Time Learning**: Learns user-specific transaction patterns based on the first 20 transactions.
- **User-Specific Models**: Trains a separate model for each user.
- **Anomaly Detection**: Detects anomalous transactions using an Isolation Forest algorithm.
- **Interactive Console Interface**: Provides a user-friendly console for inputs.

## Prerequisites

- Python 3.7 or later
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`

Install the dependencies using:

```bash
pip install pandas numpy scikit-learn

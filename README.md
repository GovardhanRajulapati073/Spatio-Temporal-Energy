# Scalable HPC-Based Spatio-Temporal Energy Demand Forecasting with CPU–GPU Hybrid Parallelism
# AI Energy Intelligence Platform (HPC Project)

## Project Overview

This project presents a High Performance Computing (HPC) based system for spatio-temporal energy consumption prediction. It focuses on forecasting energy demand, detecting peak load periods, and providing optimization recommendations using machine learning and parallel computing techniques.

The system integrates time-series analysis, machine learning models, and a web-based interface to process large-scale energy datasets efficiently.

Full Project Report: 

---

## Google Colab Notebook

Run the project directly in Google Colab:

https://colab.research.google.com/drive/1XXWmXafIbur3vGC1q_Snv_pdKzU8t0DX?usp=sharing

---

## Dataset

The project uses the UCI Household Power Consumption Dataset:

https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption

Alternatively, a synthetic dataset generator is included within the project for testing purposes.

---

## Technologies Used

* Python 3.x
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Numba (parallel processing)
* Gradio (web interface)
* Plotly (data visualization)
* Google Colab
* CUDA (optional GPU acceleration)

---

## Key Features

* Energy consumption forecasting using time-series analysis
* Peak load detection using statistical and machine learning methods
* Anomaly detection in energy usage patterns
* Interactive web-based dashboard
* Real-time simulation and visualization
* Smart grid control simulation
* High-performance execution using parallel computing

---

## System Architecture

The system follows a client–server architecture:

1. User uploads dataset via web interface
2. Gradio client sends data to backend server
3. Data preprocessing and feature engineering are performed
4. HPC-based forecasting models are applied
5. Peak load detection and analysis are executed
6. Results are generated and returned as downloadable CSV

(Refer to architecture diagram in the report, page 6)

---

## Installation and Setup

### Clone Repository

```bash
git clone https://github.com/your-username/energy-hpc-project.git
cd energy-hpc-project
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn xgboost gradio plotly numba
```

---

## How to Run

### Option 1: Google Colab (Recommended)

* Open the Colab notebook link
* Upload dataset
* Run all cells
* Access the generated Gradio interface

### Option 2: Local Execution

```bash
python hpc.py
```

After execution, open the Gradio link displayed in the terminal.

---

## Output

The system produces:

* Predicted energy consumption values
* Peak load indicators
* Peak probability scores
* Anomaly detection results
* Downloadable CSV file

---

## Sample Output Fields

* Consumption
* Predicted Energy
* Peak Probability
* Anomaly Status
* DateTime

---

## HPC Concepts Applied

* Parallel processing using Numba and multi-threaded models
* Sliding window time-series processing
* GPU acceleration in Google Colab
* Efficient large-scale data handling

---

## Future Enhancements

* Implementation of advanced deep learning models such as LSTM
* Cloud deployment using AWS or Azure
* Mobile application integration
* Integration with real-world smart grid systems

---

## Author

Rajulapati Govardhan Sai Ganesh
B.Tech CSE (Data Science)
SR University

---

## References

* Google Colab Documentation
* Pandas Documentation
* PyTorch Framework
* Gradio Documentation
* UCI Machine Learning Repository
* NVIDIA CUDA Documentation

---

# GTiS_Net
Lightweight Graph Temporal Self-Supervised Learning for Industrial IoT Anomaly Detection
# GTiS-Net

## Overview

GTiS-Net is a graph-based temporal learning framework developed for real-time anomaly detection in Industrial Internet of Things (IIoT) environments. The framework combines graph representations with temporal feature learning to model complex relationships among sensor signals and detect anomalous system behavior.
This repository contains the implementation, preprocessing pipeline, model training, evaluation scripts, and visualization tools developed during the research.


## Features

- Graph-based sensor representation
- Temporal feature extraction
- Self-supervised learning framework
- Industrial IoT anomaly detection
- Data preprocessing pipeline
- Performance evaluation
- Result visualization

## Repository Structure
GTiS-Net/
│
├── models/
├── graph_visualizations/
├── visualizations/
├── main.py
├── model.py
├── data_preprocessing.py
├── evaluate.py
├── requirements.txt
└── README.md

## Requirements

- Python 3.10+
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- NetworkX
- Matplotlib

Install dependencies

```bash
pip install -r requirements.txt

#Running

Train the model

```bash
python main.py

Evaluate

`bash
python evaluate.py


##Dataset
This implementation uses Industrial IoT datasets for anomaly detection.
If the dataset cannot be distributed due to licensing restrictions, please obtain it from the original source before running the experiments.

## Results

The framework is designed for:

- Industrial anomaly detection
- Graph temporal learning
- Self-supervised representation learning
- Real-time inference

Example visualizations are available in the `visualizations/` directory.

## Research
This repository accompanies research on graph temporal self-supervised learning for Industrial IoT anomaly detection.
If you use this repository, please cite the associated publication.

## Author
Samia Zahid

Master's Student, Computer Science

Research Interests
- Artificial Intelligence
- Machine Learning
- Computer Vision
- Graph Neural Networks
- Industrial AI

---

## License

This project is released for academic and research purposes.

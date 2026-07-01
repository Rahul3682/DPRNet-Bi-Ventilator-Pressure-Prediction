# 🫁 DPRNet-Bi: Physics-Informed Bidirectional LSTM for Ventilator Airway Pressure Prediction

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?logo=pytorch)](https://pytorch.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> A physics-informed Bidirectional LSTM framework for predicting ventilator airway pressure — built for biomedical time-series modeling and validated across datasets (Kaggle Ventilator Pressure Prediction + MIMIC-III).

![Architecture Diagram](DPRNet_Bi_architecture_diagram.png)

---

## 📖 Project Overview

DPRNet-Bi combines deep learning with physiological/physics-based constraints to predict airway pressure from ventilator sensor signals (flow, control inputs, lung resistance/compliance). The physics-informed loss term helps the model generalize better across datasets than purely data-driven baselines.

Built with **Python**, **PyTorch**, and **Google Colab**.

## 🎯 Objectives

- Predict ventilator airway pressure accurately from time-series sensor data.
- Improve generalization using physics-informed modeling (lung mechanics equation as a soft constraint).
- Benchmark against classical ML and deep learning baselines (Linear/Ridge Regression, Random Forest, LSTM, BiGRU, XGBoost, BiLSTM).
- Evaluate cross-dataset robustness on MIMIC-III.

## ✨ Key Features

- Physics-Informed Bidirectional LSTM architecture
- Multi-model statistical benchmarking (9 baseline models)
- Feature importance analysis
- Training/validation curve visualization
- Cross-dataset evaluation (MIMIC-III)
- Fully reproducible in Google Colab

## 🛠 Tech Stack

Python · PyTorch · NumPy · Pandas · Matplotlib · Scikit-learn · Joblib · Google Colab

## 📂 Project Structure

```
DPRNet-Bi-Ventilator-Pressure-Prediction/
│
├── DPRNet_Bi_FIXED_Colab_(2).ipynb     # Main training/eval notebook
├── feature_scaler.pkl                  # Saved feature scaler
├── requirements.txt
├── README.md
├── model_comparison.csv                # Baseline vs DPRNet-Bi comparison
├── DPRNet_Bi_metrics.json              # Final metrics
├── DPRNet_Bi_feature_importance.csv
├── DPRNet_Bi_architecture_diagram.png
├── DPRNet_Bi_training_curves.png
├── DPRNet_Bi_eval.png
├── DPRNet_Bi_decomposition.png
├── DPRNet_Bi_intra_breath.png
├── DPRNet_Bi_physics_params.png
└── results/
    └── mimic3/                         # Cross-dataset validation outputs
```

## 🚀 Installation

```bash
git clone https://github.com/Rahul3682/DPRNet-Bi-Ventilator-Pressure-Prediction.git
cd DPRNet-Bi-Ventilator-Pressure-Prediction
pip install -r requirements.txt
```

## ▶️ Usage

Open and run `DPRNet_Bi_FIXED_Colab_(2).ipynb` sequentially to:

1. Load and preprocess the ventilator dataset
2. Train the DPRNet-Bi model
3. Predict airway pressure
4. Evaluate against baseline models
5. Generate result visualizations

## 📊 Results

| Metric | Value (Kaggle test) |
|---|---|
| MAE | 0.0301 |
| R² | 0.9976 |

| Metric | Value (MIMIC-III cross-dataset) |
|---|---|
| MAE | 0.2841 |
| R² | 0.8888 |

> Note: MIMIC-III does not provide a direct ground-truth airway pressure signal, so cross-dataset evaluation uses a derived surrogate target — treat these numbers as a generalization sanity check rather than a formal benchmark.

### Training Curves
![Training Curves](DPRNet_Bi_training_curves.png)

### Model Evaluation
![Evaluation](DPRNet_Bi_eval.png)

### Physics Parameters
![Physics Parameters](DPRNet_Bi_physics_params.png)

### Signal Decomposition
![Decomposition](DPRNet_Bi_decomposition.png)

### Intra-Breath Analysis
![Intra-Breath](DPRNet_Bi_intra_breath.png)

## ⚠️ Note

The trained model weights (`.pt`) are not included due to GitHub's file size limits. The full training pipeline is reproducible via the provided notebook.

## 🔮 Future Work

- Transformer-based time-series models
- Explainable AI (XAI) for clinical interpretability
- Multi-center clinical validation
- Real-time ventilator monitoring integration
- Clinical decision support system

## 👨‍💻 Author

**Rahul Kumar Sah**
B.Tech Biomedical Engineering, Central University of Rajasthan
[GitHub](https://github.com/Rahul3682) · [LinkedIn](https://linkedin.com/in/rahul-kumar-sah-210970330) · rahulsah3682@gmail.com

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.

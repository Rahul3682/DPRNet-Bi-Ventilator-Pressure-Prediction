# 🫁 DPRNet-Bi: Physics-Informed Bidirectional LSTM for Ventilator Airway Pressure Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Overview

DPRNet-Bi is a Physics-Informed Bidirectional LSTM framework developed for predicting ventilator airway pressure in biomedical applications. The model combines deep learning with physiological knowledge to improve prediction accuracy, robustness, and interpretability.

This project is implemented using **Python**, **PyTorch**, and **Google Colab**.

---

## ✨ Key Features

- Physics-Informed Bidirectional LSTM Architecture
- Ventilator Airway Pressure Prediction
- Biomedical Time-Series Analysis
- Deep Learning using PyTorch
- Feature Importance Analysis
- Training & Validation Performance Visualization
- Cross-Dataset Evaluation on MIMIC-III
- Google Colab Compatible

---

## 🛠 Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

---

## 📂 Project Structure

```text
DPRNet-Bi-Ventilator-Pressure-Prediction/
│
├── DPRNet_Bi_FIXED_Colab_(2).ipynb
├── feature_scaler.pkl
├── requirements.txt
├── README.md
│
├── results/
│   ├── training/
│   ├── mimic3/
│
├── DPRNet_Bi_training_curves.png
├── DPRNet_Bi_eval.png
├── DPRNet_Bi_decomposition.png
├── DPRNet_Bi_physics_params.png
├── DPRNet_Bi_intra_breath.png
├── DPRNet_Bi_feature_importance.csv
├── DPRNet_Bi_metrics.json
└── model_comparison.csv
```

---

## 📊 Results

### Training Performance

- Training Curves
- Validation Performance
- Physics Parameter Analysis
- Feature Importance
- Model Comparison

### Cross-Dataset Evaluation

The trained model was also evaluated on the **MIMIC-III** dataset to assess its generalization capability across different clinical data distributions.

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Rahul3682/DPRNet-Bi-Ventilator-Pressure-Prediction.git
```

Move into the project folder

```bash
cd DPRNet-Bi-Ventilator-Pressure-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Open the notebook:

```text
DPRNet_Bi_FIXED_Colab_(2).ipynb
```

Run all cells sequentially to:

- Load Dataset
- Train the Model
- Evaluate Performance
- Generate Prediction Results
- Save Metrics and Visualizations

---

## 📈 Outputs

The repository contains:

- Training Curves
- Evaluation Results
- Feature Importance Analysis
- Physics Parameter Visualization
- Performance Metrics
- Model Comparison
- MIMIC-III Evaluation Results

---

## ⚠️ Note

The trained model (`.pt`) file is not included in this repository because it exceeds GitHub's web upload size limit. Users can reproduce the model by running the provided notebook.

---

## 🔮 Future Work

- Transformer-based Time-Series Models
- Multi-Hospital Validation
- Explainable AI (XAI)
- Real-Time Ventilator Prediction
- Clinical Decision Support Integration

---

## 👨‍💻 Author

**Rahul Kumar Sah**

Biomedical Engineering Graduate

Central University of Rajasthan

GitHub: https://github.com/Rahul3682

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

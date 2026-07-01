# 🫁 DPRNet-Bi: Physics-Informed Bidirectional LSTM for Ventilator Airway Pressure Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?logo=pytorch)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

DPRNet-Bi is a **Physics-Informed Bidirectional LSTM (Bi-LSTM)** framework developed for predicting ventilator airway pressure in biomedical applications. The model combines deep learning with physiological constraints to improve prediction accuracy, robustness, and interpretability.

This project is implemented using **Python**, **PyTorch**, and **Google Colab**.

---

## 🎯 Objectives

- Predict ventilator airway pressure accurately.
- Integrate physiological knowledge into deep learning.
- Improve model generalization.
- Evaluate performance on external datasets (MIMIC-III).

---

## ✨ Features

- Physics-Informed Bidirectional LSTM
- Biomedical Time-Series Prediction
- PyTorch Implementation
- Feature Importance Analysis
- Training & Validation Visualization
- Cross-Dataset Evaluation (MIMIC-III)
- Google Colab Compatible

---

## 🛠 Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Joblib
- Google Colab

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
│   └── mimic3/
│
├── model_comparison.csv
├── DPRNet_Bi_metrics.json
└── images/
```

---

## 🚀 Installation

Clone this repository:

```bash
git clone https://github.com/Rahul3682/DPRNet-Bi-Ventilator-Pressure-Prediction.git
```

Move into the project folder:

```bash
cd DPRNet-Bi-Ventilator-Pressure-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Open the notebook:

```text
DPRNet_Bi_FIXED_Colab_(2).ipynb
```

Run all notebook cells sequentially to:

- Load Dataset
- Train the Model
- Predict Airway Pressure
- Evaluate Performance
- Generate Visualizations

---

## 📊 Results

The project includes:

- ✅ Training Curves
- ✅ Validation Performance
- ✅ Model Comparison
- ✅ Feature Importance Analysis
- ✅ Physics Parameter Visualization
- ✅ Performance Metrics
- ✅ Cross-Dataset Evaluation on MIMIC-III

---

## 📸 Sample Outputs

### Training Performance

> *(Add your training curve image here)*

### Model Evaluation

> *(Add your evaluation graph here)*

### MIMIC-III Evaluation

> *(Add your MIMIC-III evaluation image here)*

---

## 📈 Model Evaluation

The proposed DPRNet-Bi model was evaluated using standard regression metrics and tested on the **MIMIC-III dataset** to assess its robustness and generalization capability.

---

## ⚠️ Note

The trained `.pt` model file is not included because it exceeds GitHub's web upload size limit. The model can be reproduced by running the provided notebook.

---

## 🔮 Future Work

- Transformer-based architectures
- Explainable AI (XAI)
- Multi-Hospital Validation
- Real-Time Deployment
- Clinical Decision Support Integration

---

## 👨‍💻 Author

**Rahul Kumar Sah**

🎓 B.Tech in Biomedical Engineering  
Central University of Rajasthan

GitHub: https://github.com/Rahul3682

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

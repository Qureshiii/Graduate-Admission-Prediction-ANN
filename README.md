# Graduate Admission Prediction using TensorFlow & Keras 🎓📈

This repository features a Deep Learning project focused on regression to predict a candidate's chance of graduate admission. Built using **TensorFlow** and **Keras**, the model maps continuous academic metrics to evaluate university selection and acceptance probabilities.

## 📌 Project Overview
Predicting university admission probabilities helps students estimate their acceptance chances before completing applications. Since this task requires predicting a continuous percentage metric (Chance of Admit ranging from 0 to 1), this pipeline applies a Regression-based Artificial Neural Network (ANN) to learn hidden non-linear combinations of candidate score cards.

## 🛠️ Tech Stack & Tools
- **Frameworks:** TensorFlow 🔥 | Keras
- **Programming & Databases:** Python | SQL
- **Data Engineering & EDA:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Kaggle Notebooks / Google Colab

## ⚙️ Engineering & Architecture Details
- **Features Processed:** GRE Score, TOEFL Score, University Rating, SOP, LOR, CGPA, and Research Experience.
- **Data Pipeline:** Implemented structural data parsing, continuous feature scaling via `StandardScaler`, and explicit matrix target splits.
- **Topology:** Multi-layered Dense Neural Network (ANN) utilizing `ReLU` activations for hidden layers and a `Linear` or `Sigmoid` activation function on the final node to scale admission chance probability outputs.
- **Optimization Stack:** Supervised tracking utilizing the `Adam` optimizer and Mean Squared Error (`MSE`) or Mean Absolute Error (`MAE`) as loss indicators.

## 📁 Project Structure
```text
├── Graduate_Admission_Prediction.ipynb  # Core Deep Learning regression pipeline notebook
└── README.md                            # Comprehensive project layout documentation
```

---
*Feel free to explore the notebook and star ⭐ this repository if you find it helpful!*


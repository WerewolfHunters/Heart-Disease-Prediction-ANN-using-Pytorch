# 🫀 Heart Disease Prediction using PyTorch

This repository contains a neural network implementation using **PyTorch** to predict heart disease based on clinical features. The model is trained on a publicly available dataset and evaluated using standard performance metrics such as accuracy, confusion matrix, precision, recall, F1-score, sensitivity, and specificity.

---

## 📂 Dataset

The dataset used is [`heart.csv`](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction), which includes the following features:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Max Heart Rate Achieved
- Exercise Induced Angina
- Oldpeak
- ST Slope
- ... and more.

The target variable is:
- `target`: 1 indicates presence of heart disease, 0 indicates absence.

---

## 🧠 Model Architecture

The neural network has the following architecture:

- **Input Layer**: Number of features in the dataset
- **Hidden Layer 1**: 64 units + ReLU
- **Hidden Layer 2**: 32 units + ReLU
- **Output Layer**: 1 unit + Sigmoid (for binary classification)

---

## 🔧 Tools & Libraries

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🚀 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/heart-disease-pytorch.git
   cd heart-disease-pytorch
   ```
2. **Install Dependencies**

  ```bash
  pip install torch pandas numpy scikit-learn matplotlib
  ```

---

## 📈 Evaluation Metrics
The model prints the following metrics after training:

 - ✅ Test Accuracy
 
 - 📊 Confusion Matrix

 - 🔍 Precision

 - 📢 Recall

 - 📐 F1 Score

 - ❤️ Sensitivity (Recall for positive class)

 - 💙 Specificity (Recall for negative class)

Also, the training loss is plotted for 1000 epochs.

---

## 📉 Sample Output

```yaml
Epoch 0, Loss: 0.6921
Epoch 100, Loss: 0.5243
...
Test Accuracy: 0.8689
Confusion Matrix:
[[24  3]
 [ 4 30]]
Sensitivity: 0.8823
Specificity: 0.8888
Precision: 0.9090
Recall: 0.8823
F1 Score: 0.8955
```

---

## 📊 Loss Curve
The training loss is visualized using Matplotlib:
![image](https://github.com/user-attachments/assets/b7c488d4-2942-44ac-992e-4a0f6ca7587b)

---

## 📃 License
This project is licensed under the MIT License. See the LICENSE file for details.

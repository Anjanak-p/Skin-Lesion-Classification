# 🔬 Skin Lesion Classification using EfficientNetB3

A deep learning project that classifies skin lesions using the **HAM10000** dataset and a fine-tuned **EfficientNetB3** model. The system is deployed through a simple **Flask web**.

---

## 📁 Dataset

- **Source**: [HAM10000 on Kaggle](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)
- **Classes**: akiec, bcc, bkl, df, mel, nv, vasc
- **Images**: 10,015 dermoscopic images of skin lesions

---

## ⚙️ Model Overview

- **Architecture**: EfficientNetB3 (transfer learning)
- **Framework**: PyTorch
- **Preprocessing**:
  - Resize to 224×224
  - Normalization
  - Data Augmentation (flip, rotate, color jitter)
- **Training**:
  - Dropout regularization
  - Softmax for 7-class output

---

## 🛠️ Tech Stack

- **Backend**: Flask, PyTorch
- **Frontend**: HTML, CSS, JavaScript
- **Data**: Pandas, NumPy

---


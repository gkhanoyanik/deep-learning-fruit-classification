# 🌿 Plant Disease Classification with ResNet50

This project focuses on the automated detection and classification of **16 different plant disease classes** and health conditions using Deep Learning. Developed as an **Industrial Engineering** project, it aims to minimize agricultural yield loss through early and accurate diagnosis.

---

## 🚀 Key Highlights
* **Architecture:** ResNet50 with **Transfer Learning** (Pre-trained on ImageNet).
* **Optimization:** Fine-tuned for real-world application with **Google Colab**.
* **Data Integrity:** Implemented a robust preprocessing pipeline to handle **noisy datasets**, including folder name correction and normalization.
* **Mobile Ready:** Model optimized and converted to **TensorFlow Lite (TFLite)** for edge deployment.

---

## 📊 Performance Analysis
The model exhibits high stability and generalization capabilities, even when faced with challenging real-world data.

| Metric | Result |
| :--- | :--- |
| **Validation Accuracy** | **96.52%** |
| **Test Accuracy (Noisy Data)** | **84.83%** |
| **Epochs to Converge** | 28 (Early Stopping Applied) |

> **Note on Model Robustness:** The significant accuracy on the "Noisy" test set demonstrates the model's ability to handle domain shifts and inconsistent labeling found in field conditions.

---

## 🛠 Tech Stack
* **Language:** `Python`
* **Deep Learning Framework:** `TensorFlow` / `Keras`
* **Architecture:** `ResNet50`
* **Optimizer:** `Adam`
* **Visualization:** `Matplotlib` & `Seaborn`

---

## 📂 Project Structure
```text
├── graphs/               # Training/Validation Accuracy & Loss curves
├── models/               # Best performing .h5 and .tflite models
├── notebooks/            # Jupyter Notebooks for model training & testing
│   ├── EE470_Building_The_Model.ipynb
│   └── EE470_Model_Testing.ipynb
├── reports/              # PDF versions of the Project Report & Presentation
└──

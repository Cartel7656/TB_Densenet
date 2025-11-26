# 🫁 Tuberculosis Detection Using DenseNet (with LIME & Grad-CAM Explainability)

This project implements a deep-learning–based **Tuberculosis (TB) detection system** using the **DenseNet** architecture, trained on chest X-ray images. It includes a complete Machine Learning (ML) pipeline, a backend API, a frontend UI, and critical explainability tools (**LIME** and **Grad-CAM**) to ensure transparency and trust in the model's decision-making process.

---

## 📌 Features

* **DenseNet Classifier:** State-of-the-art Convolutional Neural Network (CNN) for robust **TB vs. Normal** binary classification.
* **LIME Explanations:** Provides pixel-level, perturbation-based insights, highlighting superpixels that contribute most to the prediction.
* **Grad-CAM Heatmaps:** Generates visual heatmaps showing the specific lung regions the model is activating on to make a prediction. 
* **Custom Training Pipeline:** Includes data augmentation, comprehensive training, and evaluation scripts.
* **Metrics Visualization:** Automatic generation of **Confusion Matrix** and **ROC Curve** plots.
* **Full-Stack Deployment:** Includes a working **Frontend** and **Backend** for real-time, interactive predictions.
* **Modular Code:** Clear separation of concerns for training, evaluation, and serving.
* **Reproducibility:** `requirements.txt` ensures easy environment setup.

---

## 📂 Project Structure

A clean, modular structure is used for easy navigation and maintenance.

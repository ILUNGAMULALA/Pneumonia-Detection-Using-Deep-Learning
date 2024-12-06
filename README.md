# Pneumonia-Detection-Using-Deep-Learning

This repository contains a deep learning project that uses Convolutional Neural Networks (CNNs) to detect pneumonia from chest X-ray images. The model leverages Grad-CAM for visualizing important regions in the X-ray images to aid interpretability. It is specifically designed to assist healthcare professionals by providing accurate and explainable diagnoses.

## 🚀 Features

- **Pneumonia Classification:**
  - Binary classification: Pneumonia (`1`) vs Non-Pneumonia (`0`).
  - High accuracy with an ROC-AUC score of **0.93**.

- **Grad-CAM Visualizations:**
  - Highlights the most important regions of the X-ray image used by the model for predictions.

- **Custom Model Training:**
  - Training from scratch using a CNN architecture optimized for medical imaging.

- **Multi-Image Testing:**
  - Supports batch testing of multiple X-ray images with Grad-CAM overlays.

- **Explainable AI:**
  - Integrates model interpretability to ensure trust in predictions.

## 📂 Dataset

The model uses the publicly available [Chest X-ray Dataset (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).

### Dataset Structure:
chest_xray/ ├── train/ ├── test/ └── val/

- Each folder contains images of X-rays labeled as:
  - `NORMAL`: Healthy patients
  - `PNEUMONIA`: Patients with pneumonia

# Whitefly Detection with YOLOv8s

This repository contains the implementation of a whitefly detection pipeline using **YOLOv8s**, a lightweight deep learning object detection model from the Ultralytics YOLOv8 framework. The model is trained on a custom whitefly dataset to accurately detect and classify whiteflies in agricultural images.

## 📌 Project Overview

- ✅ Built using the [Ultralytics YOLOv8](https://docs.ultralytics.com/) framework
- ✅ Custom dataset configured via `google_colab_config.yaml`
- ✅ Training with `Adam` optimizer and custom hyperparameters
- ✅ Visual output: confusion matrix, training curves, validation predictions

## 🧠 Model Architecture

- **Model**: YOLOv8-S (Small variant)
- **Training Framework**: Ultralytics
- **Training Script**: Python via Google Colab
- **Optimizer**: Adam
- **Epochs**: 100
- **Batch Size**: 5
- **Initial Learning Rate**: 0.001



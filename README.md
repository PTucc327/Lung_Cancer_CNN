# Lung Cancer Detection via Convolutional Neural Networks (CNN)

## 🩺 Project Overview
This project focuses on classifying lung tissue histopathology images into three categories: **Adenocarcinoma**, **Squamous Cell Carcinoma**, and **Benign tissue**. Using the IQ-OTHNCCD dataset, I developed a Deep Learning model to assist in automated medical screening.

## 🚀 Technical Achievements
* **Architecture:** Developed a Sequential CNN with 256-128-64 filter stages and ReLU activation.
* **Performance:** Achieved **90.37% Accuracy** on unseen test data.
* **Data Engineering:** Managed 15,000+ images, utilizing `split-folders` for a robust 80/10/10 train/val/test split and `ImageDataGenerator` for real-time rescaling.
* **Iterative Debugging:** Corrected initial data-leaking and shuffling issues in the evaluation pipeline to ensure reliable clinical metrics.

## 🛠️ Tech Stack
* **Frameworks:** TensorFlow, Keras
* **Libraries:** NumPy, Pandas, Matplotlib, Scikit-learn
* **Environment:** Google Colab (GPU accelerated)

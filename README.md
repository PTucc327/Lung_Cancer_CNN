# Lung Cancer Detection via Convolutional Neural Networks (CNN)

## 🩺 Project Overview
This project focuses on classifying lung tissue histopathology images into three categories: **Adenocarcinoma**, **Squamous Cell Carcinoma**, and **Benign tissue**. Using this [**Dataset**](https://www.kaggle.com/datasets/rm1000/lung-cancer-histopathological-images/data), I developed a Deep Learning model to assist in automated medical screening. I chose to utilize the Convolutional Neural Network because of its ability to handle spatial hierachries in the medical images as compared to a standard neural network.

## 🚀 Technical Achievements
* **Architecture:** Developed a Sequential CNN with 256-128-64 filter stages and ReLU activation.
* **Performance:** Achieved **90.37% Accuracy** on unseen test data.
* **Data Engineering:** Managed 15,000+ images, utilizing `split-folders` for a robust 80/10/10 train/val/test split and `ImageDataGenerator` for real-time rescaling.
* **Iterative Debugging:** Corrected initial data-leaking and shuffling issues in the evaluation pipeline to ensure reliable clinical metrics.

## 🛠️ Tech Stack
* **Frameworks:** TensorFlow, Keras
* **Libraries:** NumPy, Pandas, Matplotlib, Scikit-learn
* **Environment:** Google Colab (GPU accelerated)

## Improvements

During the original project, I created a Convolutional Neural Network with an overall accuracy of 98% for training data but a 32% accuracy on my test data creating a very overfit model. To combat this I changed the model parameters, the original model started at 32 nodes and then increased to 128 then classified my data into 1 of the 3 categories. The new model I created, starts at 256 nodes, and goes down to 32 then classifies the data. This new method greatly improved results for the test data as shown in the image below.

## Results
![Confusion Matrix](confusion_matrix_image.png)




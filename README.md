# Diabetic-Retinopathy-Detection-using-Transfer-learning-using-Resnet50
DATASET LINK FROM KAGGLE:https://www.kaggle.com/datasets/shajinrp/diabetic-retinopathy
🩺 Diabetic Retinopathy Detection using Transfer Learning (ResNet-50)
📌 Project Overview

Diabetic Retinopathy (DR) is a diabetes-related eye disease that can lead to irreversible blindness if not detected early. This project focuses on the automated detection of Diabetic Retinopathy from retinal fundus images using deep learning and transfer learning techniques.

A pretrained ResNet-50 convolutional neural network is employed as the feature extraction backbone, enabling efficient learning of complex retinal patterns even with a limited dataset.

🎯 Objectives

Automatically classify retinal images as Diabetic Retinopathy or Normal

Reduce dependency on manual ophthalmological screening

Improve early detection accuracy using deep learning

🧠 Methodology

Transfer Learning is applied using ResNet-50, pretrained on ImageNet

The final classification layers are fine-tuned on a labeled retinal image dataset

The model learns disease-specific features such as:

Microaneurysms

Hemorrhages

Exudates

Blood vessel abnormalities

🏗️ System Architecture

Input: Retinal fundus images

Preprocessing:

Image resizing

Normalization

Data augmentation

Feature Extraction:

ResNet-50 pretrained CNN

Classification:

Fully connected layers

Softmax / Sigmoid output

Output:

Diabetic Retinopathy detected / not detected

🛠️ Technologies Used

Python

TensorFlow / Keras

ResNet-50 (Transfer Learning)

NumPy, OpenCV

Matplotlib

Jupyter Notebook / Flask (optional deployment)

📊 Model Performance

Achieves high accuracy due to deep residual learning

Reduces overfitting through pretrained weights and augmentation

Efficient training compared to CNNs trained from scratch

🚀 Applications

Clinical decision support systems

Automated eye screening tools

Telemedicine platforms

Early detection in rural and low-resource healthcare settings

🔮 Future Enhancements

Multi-class DR severity classification

Integration with web or mobile applications

Explainable AI (Grad-CAM visualization)

Larger and more diverse datasets

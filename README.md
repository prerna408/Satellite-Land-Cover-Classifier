# Satellite Land-Cover Classification (AI/ML)

## Project Overview
This project implements a Deep Learning solution for automated land-cover mapping. Using the **EuroSAT (RGB)** dataset, I developed a Computer Vision model that classifies satellite imagery into 10 distinct terrain categories, such as Forest, River, Crops, and Residential areas.

## Technical Architecture
* **Backbone:** MobileNetV2 (Transfer Learning from ImageNet)
* **Framework:** TensorFlow / Keras
* **Methodology:** I utilized a frozen pre-trained base for feature extraction, followed by Global Average Pooling and a specialized Softmax output layer.
* **Optimization:** Adam optimizer with Sparse Categorical Crossentropy loss.

## Results & Metrics
* **Validation Accuracy:** ~80.6%
* **Validation Loss:** 0.5458
* **Training Time:** ~90 seconds (3 epochs on T4 GPU)

## Visual Verification
(Below is a sample of the model correctly identifying diverse terrains from the validation set.)

![Model Predictions]([<img width="1132" height="669" alt="image" src="https://github.com/user-attachments/assets/01e8a856-4da1-492d-ae06-38ad3f31f426" />](https://github.com/prerna408/Satellite-Land-Cover-Classifier/blob/main/Screenshot%202026-01-31%20223024.png?raw=true)
)


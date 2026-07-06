# 🌿 Plant Disease Detection Using Deep Learning

## Overview

This project implements a Convolutional Neural Network (CNN) to automatically classify plant diseases from leaf images. Early detection of plant diseases is essential for improving crop productivity, reducing economic losses, and supporting sustainable agriculture.

The model is trained on labeled images of healthy and diseased plant leaves and predicts the disease category from an input image.

This project demonstrates my understanding of image preprocessing, deep learning, model evaluation, and computer vision using Python and TensorFlow.

---

## Objectives

- Develop an automated plant disease classification system.
- Learn and apply Convolutional Neural Networks (CNNs).
- Explore image preprocessing techniques.
- Evaluate model performance using classification metrics.
- Build a reusable deep learning pipeline for image classification.

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV (if applicable)
- Scikit-learn
- Google Colab

---

## Dataset

The project uses a publicly available plant disease image dataset containing images of healthy and diseased plant leaves.

Dataset includes:

- Multiple plant species
- Multiple disease classes
- Healthy leaf images
- RGB leaf photographs

**Note:** The dataset is not included in this repository due to its large size.

---

## Project Structure

```
plant-disease-classification/
│
├── Plant_Disease_Detection.ipynb
├── README.md
├── requirements.txt
├── images/
│
└── results/
```

---

## Workflow

### 1. Data Loading

- Load plant leaf images
- Organize labels
- Split into training and validation sets

### 2. Data Preprocessing

- Resize images
- Normalize pixel values
- Convert labels
- Data augmentation (if used)

### 3. Model Development

A Convolutional Neural Network (CNN) was built using TensorFlow/Keras to classify plant diseases.

Typical CNN architecture includes:

- Convolution layers
- Max Pooling layers
- ReLU activation
- Dropout
- Dense layers
- Softmax output layer

---

## Model Training

The model was trained using:

- Categorical Crossentropy Loss
- Adam Optimizer
- Mini-batch Gradient Descent
- Validation Monitoring

---

## Model Evaluation

Performance was evaluated using:

- Accuracy
- Loss Curves
- Validation Accuracy
- Prediction Examples

Future versions may include:

- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Results

The trained CNN successfully learned to distinguish between healthy and diseased plant leaves.

The project demonstrates how deep learning can assist agricultural disease diagnosis through automated image classification.

---

## Skills Demonstrated

This project demonstrates practical experience in:

- Computer Vision
- Deep Learning
- Convolutional Neural Networks
- Data Preprocessing
- Image Classification
- Model Training
- Model Evaluation
- Python Programming
- TensorFlow
- Machine Learning Workflow

---

## Future Improvements

Possible future enhancements include:

- Transfer Learning using EfficientNet or ResNet
- Mobile application deployment
- Web application using Flask or Streamlit
- Real-time disease detection
- Disease severity estimation
- Support for additional crop species
- Improved model accuracy through hyperparameter tuning

---

## Applications

Potential applications include:

- Smart agriculture
- Crop monitoring
- Agricultural decision support
- Mobile farming assistants
- Precision agriculture

---



## Requirements

Example packages:

```
tensorflow
numpy
pandas
matplotlib
opencv-python
scikit-learn
```

---

## Author

**RUHAMA SOLOMON **

Aspiring Data Scientist interested in Machine Learning, Computer Vision, and AI applications for real-world challenges.

---

## License

This project is intended for educational and research purposes.

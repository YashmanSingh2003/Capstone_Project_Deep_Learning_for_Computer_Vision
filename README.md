# DeepFER - Facial Emotion Recognition Using Deep Learning

## Overview

DeepFER is a deep learning project that recognizes human emotions from facial expressions using a Convolutional Neural Network (CNN). The model classifies facial images into seven emotion categories and demonstrates the complete deep learning workflow, from data preprocessing to real-time emotion prediction.

This project was developed using TensorFlow/Keras and OpenCV and serves as a practical implementation of facial emotion recognition.

---

## Features

- Facial emotion recognition using CNN
- Data preprocessing and normalization
- Data augmentation for improved generalization
- Model training and validation
- Emotion prediction on unseen images
- Real-time emotion recognition using a webcam
- Emotion prediction on custom images
- Model saving for future deployment

---

## Emotion Classes

The model classifies facial expressions into the following seven categories:

- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

---

## Dataset

This project uses the **FER2013** facial emotion recognition dataset.

Dataset characteristics:

- 48 × 48 grayscale facial images
- Seven emotion classes
- Thousands of labeled facial images
- Suitable for deep learning applications

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn

---

## Project Workflow

1. Load the FER2013 dataset
2. Perform data preprocessing
3. Normalize pixel values
4. Apply one-hot encoding
5. Split the dataset into training, validation, and testing sets
6. Perform data augmentation
7. Build the CNN model
8. Train the model
9. Evaluate model performance
10. Save the trained model
11. Predict emotions on test images
12. Perform real-time emotion recognition using a webcam

---

## CNN Architecture

The model consists of:

- 3 Convolutional Layers
- Batch Normalization
- Max Pooling Layers
- Flatten Layer
- Dense Layer
- Dropout Layer
- Softmax Output Layer

Loss Function:
- Categorical Crossentropy

Optimizer:
- Adam

Evaluation Metric:
- Accuracy

---

## Results

Model Performance:

- Training Accuracy: **48.8%**
- Best Validation Accuracy: **53.5%**
- Test Accuracy: **54.86%**

The model demonstrates the ability to classify human facial emotions with moderate accuracy and serves as a strong baseline CNN implementation.

---

## Applications

- Human-Computer Interaction
- Mental Health Monitoring
- Customer Experience Analysis
- Smart Education
- Healthcare
- Security and Surveillance
- Driver Monitoring Systems
- Emotion-Aware AI Systems

---

## Future Improvements

Potential enhancements include:

- Transfer Learning (VGG16, ResNet50, EfficientNet, MobileNet)
- Hyperparameter Optimization
- Larger and More Diverse Datasets
- Attention Mechanisms
- Model Quantization
- Web Application Deployment
- Mobile Application Integration

---

## Repository Structure

```
DeepFER/
│
├── DeepFER.ipynb              # Google Colab Notebook
├── deepfer_model.h5           # Trained CNN Model
├── deepfer_live.py            # Real-time Emotion Recognition
├── README.md                  # Project Documentation
├── images/                    # Dataset Images
└── requirements.txt           # Project Dependencies (optional)
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/DeepFER.git
```

Navigate to the project directory:

```bash
cd DeepFER
```

Install dependencies:

```bash
pip install tensorflow keras opencv-python matplotlib numpy pandas scikit-learn
```

---

## Usage

Train the model using the notebook:

```
DeepFER.ipynb
```

For real-time emotion recognition:

```bash
python deepfer_live.py
```

To test on a custom image:

- Load the saved model
- Provide the image path
- Run the prediction cell

---

## Conclusion

DeepFER demonstrates how Convolutional Neural Networks can be applied to facial emotion recognition. The project covers the complete deep learning pipeline, including preprocessing, model development, training, evaluation, and deployment. Although the model achieves moderate accuracy, it provides a solid foundation for further improvements using advanced deep learning techniques and transfer learning.

---

## Author

**Yashman Singh**

Master's in Computer Science (Data Science & AI)

Interested in Data Science, Machine Learning, Computer Vision, and Deep Learning.

# Face_Emotion_Recognition_Machine_Learning
Face Emotion Recognition using Machine Learning Python

#  Face Emotion Recognition Model

This project is a Deep Learning-based Face Emotion Recognition system designed to detect and classify human emotions from facial images in real-time. It leverages Convolutional Neural Networks (CNN), along with other Machine Learning models like SVM and basic Neural Networks to achieve robust emotion classification.

---

## 📌 Overview

The model is trained to recognize **basic facial emotions** such as:
- Happy 😊
- Sad 😢
- Angry 😠
- Surprise 😲
- Neutral 😐  
... and more, depending on the dataset labels.

**Use Case:**  
This system can be integrated into **online exam proctoring environments** to monitor and flag suspicious or emotionally intense behavior by students during tests.

---

## 🧠 Technologies & Libraries Used

- TensorFlow / Keras – Deep Learning framework for building CNN models  
- **OpenCV** – Real-time face detection and image preprocessing  
- **scikit-learn** – Traditional ML models (SVM, evaluation)  
- **pandas / NumPy** – Data manipulation and processing  
- **tqdm** – Progress bar for model training  
- **matplotlib / seaborn** – (Optional) Visualization of training history and confusion matrices

---

## 📊 Dataset

- Used a custom dataset of **7,000+ labeled facial images**  
- Images were preprocessed (grayscale, resized, normalized) before training  
- Emotions were labeled into categories (e.g., happy, sad, angry, etc.)

---

## 🎯 Model Performance

- Achieved up to **80% accuracy** on the test set
- Evaluated using metrics like confusion matrix, precision, and recall

---

## 🛠 How to Run

1. Clone the repository  
2. Install the required libraries  
3. Run the training script:
   ```bash
   python train_model.py


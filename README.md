# 🏃 Human Activity Recognition (HAR) using Deep Learning

This repository contains implementations of multiple deep learning models to classify human activities from sensor data.  
We explore **CNN**, **VGG16**, **DenseNet**, **CNN-LSTM**, **MobileNetV2**, and **EfficientNetB0** architectures (with and without fine-tuning), and compare their performance.

---

## 📌 Project Overview

Human Activity Recognition (HAR) is the task of predicting human actions (like walking, standing, sitting, etc.) from time-series signals such as accelerometer and gyroscope data.  
This project demonstrates how deep learning architectures can be applied for HAR and benchmarks different models.

---

## 📊 Dataset

- **Dataset Used:** 📂 *[https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones]*
- **Features:** Accelerometer & gyroscope signals (time-series)
- **Labels:** [Walking, Standing, Sitting, Lying Down, etc.]

---

## 🏗️ Models Implemented

We experimented with multiple architectures:

1. **CNN** – For extracting local spatial patterns in the sensor data  
2. **VGG16** – Transfer learning for deeper feature extraction  
3. **DenseNet** – Densely connected convolutional networks for efficient feature usage  
4. **CNN-LSTM** – Combining CNN feature extraction with sequence modeling  
5. **MobileNetV2** – Lightweight and efficient neural network architecture (with and without fine-tuning)  
6. **EfficientNetB0** – State-of-the-art scalable model (with and without fine-tuning)  

---

## 📈 Results

| Model                             | Train Accuracy (%) | Test Accuracy (%) | Notes                                  |
|------------------------------------|-------------------|-------------------|----------------------------------------|
| CNN                               | 71.33             | 80.22             | Baseline convolutional approach        |
| VGG16                             | 76.32             | 85.97             | Transfer learning with VGG16           |
| DenseNet                          | 87.83             | 92.33             | Dense connections improve performance  |
| CNN-LSTM                          | 98.83             | 95.00             | Combines CNN + LSTM strengths          |
| MobileNetV2                       | 94.96             | 96.64             | Lightweight, fast, accurate            |
| MobileNetV2 (Fine-tuned)          | 95.11             | 97.84             | Fine-tuning boosts performance         |
| EfficientNetB0                    | 98.35             | 97.36             | SOTA results before fine-tuning        |
| EfficientNetB0 (Fine-tuned)       | 98.08             | 98.68             | **Best overall performance**           |

**EfficientNetB0 is the winner:**  
- Before fine-tuning: 49.7 minutes training time  
- After fine-tuning: 30.98 minutes training time  
- Highest test accuracy: **98.68%**

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/shashankkusu/human-activity-recognition.git
   cd human-activity-recognition
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook "human activity recognition.ipynb"
   ```

---

## 📦 Dependencies

- Python 3.x
- TensorFlow / Keras
- NumPy, Pandas, Scikit-learn
- Matplotlib, Seaborn

(See `requirements.txt` for exact versions)

---

## 📌 Future Work

- Try transformer-based models for HAR
- Apply transfer learning from pretrained sequence models
- Deploy the best model into a mobile app / edge device

---

## 👨‍💻 Author

**K. Shashank**

⭐ If you find this project helpful, don’t forget to give it a star on GitHub!

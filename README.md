# 🏃 Human Activity Recognition (HAR) using Deep Learning

This repository contains implementations of multiple deep learning models to classify human activities from sensor data.  
We explore **CNN**, **LSTM**, **CNN-LSTM**, and **ConvLSTM** architectures and compare their performance.

---

## 📌 Project Overview

Human Activity Recognition (HAR) is the task of predicting human actions (like walking, standing, sitting, etc.) from time-series signals such as accelerometer and gyroscope data.  
This project demonstrates how deep learning architectures can be applied for HAR and benchmarks different models.

---

## 📊 Dataset

- **Dataset Used:** 📂 *[Add dataset name here — e.g., UCI HAR Dataset / Custom Dataset]*
- **Features:** Accelerometer & gyroscope signals (time-series)
- **Labels:** [Walking, Standing, Sitting, Lying Down, etc. (update with actual labels used in your notebook)]

---

## 🏗️ Models Implemented

We experimented with multiple architectures:

1. **CNN** – For extracting local spatial patterns in the sensor data  
2. **LSTM** – To capture temporal dependencies in the sequence  
3. **CNN-LSTM** – Combining CNN feature extraction with sequence modeling  
4. **ConvLSTM** – Spatiotemporal modeling for activity recognition  

---

## 📈 Results

| Model      | Accuracy | Notes |
|------------|----------|-------|
| CNN        | XX%      | Baseline convolutional approach |
| LSTM       | XX%      | Captures sequential dependencies |
| CNN-LSTM   | XX%      | Combines CNN + LSTM strengths |
| ConvLSTM   | XX%      | Best performing model (if true) |

*(Replace `XX%` with actual results from your notebook)*

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/human-activity-recognition.git
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

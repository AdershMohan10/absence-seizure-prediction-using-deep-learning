# 🧠 Epileptic Seizure Prediction Using Deep Learning  
**Deep Learning for EEG Signal Classification**  
**Author:** Adersh Mohan Puthiyedath  

---

## 📌 Project Overview

This project presents a deep learning-based system for the **early prediction of epileptic seizures** using EEG signals. The model combines **Convolutional Neural Networks (CNNs)** and **Long Short-Term Memory (LSTM)** networks to detect spatiotemporal patterns in brain signals, offering real-time seizure prediction.

---

## 🎯 Objectives

- 🔄 Real-time seizure prediction from EEG signals  
- ⚠️ Early alerts for clinical intervention  
- 💡 Improve model accuracy across diverse patients  
- 📉 Reduce false positives and manual feature engineering

---

## 🛠️ Technologies Used

| Tool/Library           | Purpose                                |
|------------------------|----------------------------------------|
| Python                 | Core programming language              |
| TensorFlow / Keras     | Deep learning framework                |
| pandas, numpy          | Data manipulation                      |
| matplotlib, seaborn    | Data visualization and EDA             |
| Flask                  | Web app backend (`app.py`)             |
| .h5 model              | Trained CNN-LSTM model for inference   |

---

## 📁 Repository Structure

epileptic-seizure-prediction-using-deep-learning/
├── README.md → Project documentation
├── app.py → Flask app to serve the model
├── copy_of_lstm_cnn_seizure.py → CNN-LSTM model building & training
├── eda_for_epilepsy.py → Exploratory Data Analysis script
├── my_cnn_lstm_model.h5 → Trained model for inference


---

## 🔍 File Descriptions

- **`app.py`**: Flask application that loads and runs the trained model  
- **`copy_of_lstm_cnn_seizure.py`**: Main script for building and training the CNN-LSTM model  
- **`eda_for_epilepsy.py`**: Generates visual insights from EEG data  
- **`my_cnn_lstm_model.h5`**: Saved trained model (ready for deployment)

---

## 🧪 Methodology

1. **Preprocessing**: EEG signal filtering, normalization, and segmentation  
2. **EDA**: Understanding seizure vs non-seizure patterns through visualization  
3. **Model Architecture**:
   - CNN layers extract spatial features
   - LSTM layers capture temporal dependencies  
4. **Evaluation**: Accuracy, confusion matrix, ROC-AUC, etc.  
5. **Deployment**: Real-time interface via Flask (`app.py`)

---

## ✅ Results

- CNN-LSTM architecture effectively predicts epileptic seizures  
- Improved classification performance with reduced false positives  
- Suitable for integration in future real-time EEG monitoring systems


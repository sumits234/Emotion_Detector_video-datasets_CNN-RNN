<div align="center">

# 😊 Emotion Detector using Video Datasets (CNN + RNN)
### Video-based Emotion Recognition using Deep Learning (Feature Extraction + Sequence Modeling)

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Deep Learning](https://img.shields.io/badge/DeepLearning-CNN%20%2B%20RNN-green.svg)]()
[![Video](https://img.shields.io/badge/Data-Video%20Dataset-orange.svg)]()
[![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)](#license)

🔗 **GitHub Repo:** https://github.com/sumits234/Emotion_Detector_video-datasets_CNN-RNN

</div>

---

## 🚀 Project Overview
This project implements an **Emotion Detection / Recognition system** using **video datasets** by combining:
- **CNN** for extracting spatial features from frames
- **RNN (LSTM)** for modeling temporal sequence patterns across frames

The model learns emotions from **facial expressions in videos** and predicts the emotion class for input video clips.

---

## ✨ Key Features
✅ Video frame extraction & preprocessing  
✅ CNN-based frame-level feature extraction  
✅ RNN-based sequence learning (video-level prediction)  
✅ End-to-end training & evaluation pipeline  
✅ Supports multi-class emotion classification  

---

## 🧠 Tech Stack
- **Python**
- **OpenCV** (video/frame processing)
- **TensorFlow / Keras** *(or PyTorch if you used it)*
- **NumPy / Pandas**
- **Matplotlib** (visualization)

---

## ⚙️ Workflow / Architecture
```txt
Video Dataset
   ↓
Frame Extraction (OpenCV)
   ↓
Preprocessing (Resize, Normalize)
   ↓
CNN → Frame Feature Vectors
   ↓
RNN (LSTM/GRU) → Temporal Learning
   ↓
Emotion Prediction

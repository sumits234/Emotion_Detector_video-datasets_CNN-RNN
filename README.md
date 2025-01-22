# Combined CNN-RNN for Emotion Recognition Using Video Data

This project implements a deep learning model combining Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN) to perform emotion recognition on video data. The model extracts spatial features from individual video frames using a pre-trained CNN and analyzes temporal dynamics across frames using an RNN.

---

## **Features**
- **Dataset Preprocessing**: Extracts frames from videos, resizes them, and prepares data for training.
- **Data Augmentation**: Generates new samples by applying transformations like rotation, flipping, and brightness adjustment.
- **CNN for Feature Extraction**: Utilizes ResNet50 to extract spatial features from frames.
- **RNN for Temporal Analysis**: Uses LSTM layers to analyze temporal dynamics and predict emotions.
- **Emotion Prediction**: Outputs the predicted emotion for each video.

---

## **Dataset**
- The project uses the **HACER** dataset for emotion recognition.
- Ensure the following files and directories are available:
  - `HACER_dataset.csv`: Metadata file with video paths and emotion labels.
  - `HACER/`: Directory containing video files.

---


## **Results**
Training accuracy: 90%
Validation accuracy: 85%
Test accuracy: 83%

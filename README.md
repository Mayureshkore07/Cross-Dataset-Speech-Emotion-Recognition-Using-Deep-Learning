# 🎙️ Cross-Dataset Speech Emotion Recognition Using Deep Learning Models

> A comprehensive deep learning framework for cross-dataset Speech Emotion Recognition (SER) using the **RAVDESS** and **CREMA-D** datasets. This project investigates multiple machine learning, deep learning, transfer learning, and transformer-based architectures to identify the most effective model for robust emotion classification across different speech datasets.

---

## 📌 Project Overview

Speech Emotion Recognition (SER) plays an important role in human-computer interaction, healthcare, virtual assistants, education, and intelligent conversational systems. However, most existing SER models perform well only on the dataset they are trained on and struggle to generalize across unseen datasets.

This project addresses this challenge by developing a **cross-dataset Speech Emotion Recognition framework** using the **RAVDESS** and **CREMA-D** datasets. Multiple approaches—including traditional machine learning, deep learning, transfer learning, and transformer-based architectures—were systematically explored and compared. The final implementation employs a **Convolutional Recurrent Neural Network (CRNN)** combining CNN and BiLSTM layers, which achieved the best overall performance among the evaluated models.

---

# ✨ Features

- 🎙️ Cross-dataset Speech Emotion Recognition using **RAVDESS** and **CREMA-D**
- 🎧 Audio preprocessing and dataset standardization
- 📊 Log-Mel Spectrogram feature extraction
- 🤖 Comparative analysis of multiple Machine Learning and Deep Learning models
- 🧠 Evaluation of CNN, CRNN, LSTM, SVM, DANN, HuBERT, Whisper, and Wav2Vec-based approaches
- 📈 Performance evaluation using Accuracy, Confusion Matrix, Precision, Recall, and F1-Score
- 🏆 Final CRNN (CNN + BiLSTM) architecture achieving the best overall performance
- 📚 Well-organized research workflow from preprocessing to final model evaluation

- ---

# 🔄 Project Workflow

This project follows a structured research workflow, starting from dataset preparation to final model evaluation.

```text
RAVDESS Dataset          CREMA-D Dataset
        │                      │
        └──────────┬───────────┘
                   │
                   ▼
         Audio Preprocessing
                   │
                   ▼
      Dataset Standardization
                   │
                   ▼
  Log-Mel Spectrogram Extraction
                   │
                   ▼
      Research Experiments
 (CNN, CRNN, DANN, HuBERT,
 Whisper, Wav2Vec, Ensemble)
                   │
                   ▼
        Model Comparison
 (CRNN, CNN, LSTM and SVM)
                   │
                   ▼
     Final CRNN Architecture
          (CNN + BiLSTM)
                   │
                   ▼
      Emotion Classification
```

The project was developed in multiple stages. Initially, both speech datasets were preprocessed and standardized to ensure consistency. Log-Mel spectrogram features were extracted and used for model training. Multiple machine learning, deep learning, transfer learning, and transformer-based architectures were then explored. Finally, a comparative evaluation identified the CRNN (CNN + BiLSTM) architecture as the best-performing model for the three-emotion cross-dataset classification task.

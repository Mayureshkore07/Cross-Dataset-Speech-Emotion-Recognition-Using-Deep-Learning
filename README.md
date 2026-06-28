# 🎙️ Cross-Dataset Speech Emotion Recognition Using Deep Learning Models

> A comprehensive Speech Emotion Recognition (SER) project that investigates multiple Machine Learning, Deep Learning, Domain Adaptation, and Transformer-based architectures using the **RAVDESS** and **CREMA-D** datasets. The project focuses on evaluating different approaches for cross-dataset emotion recognition and identifying robust models for real-world speech emotion classification.

---

# 📌 Project Overview

Speech Emotion Recognition (SER) is an important research area in Artificial Intelligence that enables machines to understand human emotions from speech signals. It has applications in healthcare, intelligent virtual assistants, human-computer interaction, education, customer service, mental health monitoring, and conversational AI.

Although many SER models achieve excellent performance on individual datasets, they often fail to generalize when evaluated on unseen datasets due to differences in speakers, recording environments, and speech characteristics.

This project addresses this challenge by performing a comprehensive comparative study using two publicly available emotional speech datasets: **RAVDESS** and **CREMA-D**. Throughout this research, multiple Machine Learning, Deep Learning, Domain Adaptation, and Transformer-based architectures were explored and compared to analyze their effectiveness for cross-dataset Speech Emotion Recognition.

Rather than focusing on a single model, this repository documents the complete research journey—from dataset preparation and feature extraction to extensive experimentation, model comparison, and final implementations.

---

# 🚀 Project Highlights

* 🎙️ Cross-Dataset Speech Emotion Recognition using **RAVDESS** and **CREMA-D**
* 🎧 End-to-end audio preprocessing and dataset standardization
* 📊 Log-Mel Spectrogram feature extraction
* 🤖 Comparative evaluation of **9+ Machine Learning, Deep Learning, and Transformer-based models**
* 🧠 Implemented CNN, CRNN, LSTM, SVM, DANN, Wav2Vec, HuBERT, Whisper, and Ensemble architectures
* 🏆 **Highest Accuracy Model:** CNN (**82.60%**)
* ⭐ **Best Hybrid Model:** CRNN (CNN + BiLSTM) (**80.56%**)
* 📈 Complete research workflow from dataset preparation to final model comparison
* 📚 Well-organized repository containing preprocessing, experimentation, evaluation, and final implementations

---

# ✨ Features

* Cross-Dataset Speech Emotion Recognition using **RAVDESS** and **CREMA-D**
* Audio preprocessing and dataset standardization
* Log-Mel Spectrogram feature extraction
* Comparative analysis of Machine Learning, Deep Learning, Domain Adaptation, and Transformer models
* Evaluation of CNN, CRNN, LSTM, SVM, DANN, Wav2Vec, HuBERT, Whisper, and Ensemble architectures
* Performance evaluation using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
* Includes both the **Highest Accuracy CNN Model** and the **Best Hybrid CRNN Model**
* Organized research workflow from preprocessing to final model implementations

---

# 🔄 Project Workflow

```text
                  RAVDESS Dataset
                         │
                         │
                  CREMA-D Dataset
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
      ┌─────────────────────────────┐
      │ CNN                         │
      │ CRNN                        │
      │ LSTM                        │
      │ SVM                         │
      │ DANN                        │
      │ Wav2Vec + DANN              │
      │ HuBERT                      │
      │ Whisper                     │
      │ CNN + CRNN Ensemble         │
      └─────────────────────────────┘
                         │
                         ▼
             Comparative Evaluation
                         │
                         ▼
                Final CNN & CRNN Models
                         │
                         ▼
          Speech Emotion Classification
```

The project follows a structured research workflow beginning with dataset preparation, preprocessing, and feature extraction. Multiple Machine Learning, Deep Learning, Domain Adaptation, and Transformer-based architectures were implemented and evaluated. Finally, comparative analysis identified two key implementations included in this repository: the **CNN model**, which achieved the highest classification accuracy, and the **CRNN (CNN + BiLSTM)** model, which represents the strongest hybrid architecture explored during the study.

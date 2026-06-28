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

---

# 📂 Repository Structure

```text
Cross-Dataset-Speech-Emotion-Recognition-Using-Deep-Learning/
│
├── assets/
│   ├── accuracy_curve.png
│   ├── loss_curve.png
│   ├── confusion_matrix.png
│   ├── dataset_distribution.png
│   ├── model_architecture.png
│   └── ...
│
├── data/
│
├── models/
│
├── notebooks/
│   ├── 01_Data_Preparation/
│   ├── 02_Research_Experiments/
│   ├── 03_Model_Comparison/
│   └── 04_Final_Model/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

### Folder Description

| Folder | Description |
|---------|-------------|
| **assets/** | Images, plots, architecture diagrams, confusion matrices, and project visualizations. |
| **data/** | Dataset information and references for RAVDESS and CREMA-D. |
| **models/** | Directory reserved for trained model files and checkpoints. |
| **notebooks/** | Complete research workflow, from data preparation to the final CRNN implementation. |

---

# 📊 Datasets

This project utilizes two publicly available emotional speech datasets to evaluate the robustness and generalization capability of Speech Emotion Recognition (SER) models.

## 1. RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)

- Professional emotional speech recordings
- High-quality audio with balanced emotional classes
- Widely used benchmark dataset for Speech Emotion Recognition research

## 2. CREMA-D (Crowd-sourced Emotional Multimodal Actors Dataset)

- Large collection of emotional speech recordings
- Multiple speakers with diverse age groups and genders
- Provides greater variability for evaluating model generalization

## Cross-Dataset Evaluation

Unlike traditional Speech Emotion Recognition studies that train and evaluate on a single dataset, this project investigates **cross-dataset learning** using both **RAVDESS** and **CREMA-D**. This approach helps evaluate how well models generalize across different recording conditions, speakers, and speech styles, making the evaluation more representative of real-world applications.

> **Note:** The original datasets are not included in this repository because of their size and licensing restrictions. They can be downloaded from their respective official sources.

---

# 🧠 Models Explored

This project investigates multiple machine learning, deep learning, transfer learning, and transformer-based architectures for cross-dataset Speech Emotion Recognition.

| Model | Category | Purpose |
|--------|----------|---------|
| CNN | Deep Learning | Baseline model using Log-Mel Spectrogram features |
| CRNN (CNN + BiLSTM) | Deep Learning | Final architecture combining spatial and temporal feature learning |
| LSTM | Deep Learning | Sequential modeling baseline |
| SVM | Machine Learning | Traditional machine learning baseline |
| DANN | Domain Adaptation | Improve cross-dataset generalization |
| Wav2Vec + DANN | Self-Supervised + Domain Adaptation | Robust speech representation learning |
| HuBERT | Self-Supervised Transformer | Pre-trained speech representation model |
| Whisper | Foundation Model | Transformer-based speech feature extraction |
| CNN + CRNN Ensemble | Ensemble Learning | Combined predictions from multiple architectures |

> After extensive experimentation and comparative evaluation, the **CRNN (CNN + BiLSTM)** architecture achieved the best overall performance and was selected as the final model for this project.

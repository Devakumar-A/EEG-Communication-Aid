# 🧠 NeuroSense: Deep Learning-Based EEG Communication Aid for Paralyzed Patients

A Deep Learning-powered Brain-Computer Interface (BCI) system designed to assist paralyzed and severely motor-impaired patients by interpreting EEG signals for communication, emotion recognition, and pain severity assessment.

This project integrates multiple healthcare functionalities into a single EEG-based framework, enabling real-time interaction and physiological monitoring without physical movement.

---

## 📄 Research Publication

**Title:** Deep Learning-Based EEG Communication Aid for Paralyzed Patients

**Journal:** International Journal of Drug Delivery Technology (IJDDT)

**Volume:** 16 (58s), 2026

**DOI:** 10.25258/IJDDT.16.58S.21

**Authors:**
- Dr. R. G. Suresh Kumar
- Devakumar A
- Roney Varughese Joseph
- Sivasubramanian J

---

## 🎯 Project Overview

Individuals suffering from severe motor impairments, paralysis, or Locked-In Syndrome often lose the ability to communicate through conventional methods.

This project introduces an EEG-based Brain-Computer Interface capable of:

- Communication Intent Detection
- Emotion Recognition
- Pain Severity Assessment
- Real-Time Assistive Feedback

The system analyzes brain activity signals captured through Electroencephalography (EEG) and converts them into meaningful outputs that can assist both patients and caregivers.

---

## 🚀 Key Features

### 🧠 EEG-Based Communication

Detects user intent directly from EEG brain signals and converts it into predefined communication commands.

Example outputs:

- I Need Help
- I Am In Pain
- Emergency Alert
- Assistance Required

---

### 😊 Emotion Recognition

Identifies emotional states from EEG patterns.

Supported states include:

- Calm
- Stress
- Distress
- Anxiety

---

### ❤️ Pain Severity Detection

Monitors pain-related EEG patterns and classifies severity levels.

Categories:

- Mild
- Moderate
- Severe

---

### ⚡ Real-Time Processing

Designed as a continuous processing pipeline that performs:

- EEG Signal Acquisition
- Signal Preprocessing
- Feature Extraction
- Classification
- Output Generation

in real time.

---

## 🏗 System Architecture

```text
EEG Signal Acquisition
          │
          ▼
Signal Preprocessing
(Bandpass Filtering,
Normalization,
Artifact Removal)
          │
          ▼
Feature Extraction
(EEGNet Inspired CNN)
          │
          ▼
Multi-Task Classification
 ├── Intent Detection
 ├── Emotion Recognition
 └── Pain Severity Detection
          │
          ▼
Assistive Output Interface
          │
          ▼
Caregiver / Patient Dashboard
```

---

## 🔬 Methodology

### Step 1: EEG Signal Acquisition

Brain activity signals are collected using non-invasive EEG devices.

---

### Step 2: EEG Preprocessing

The raw EEG signals undergo preprocessing:

- Band-pass Filtering (1–40 Hz)
- Noise Reduction
- Artifact Removal
- Normalization
- Segmentation

This improves signal quality before classification.

---

### Step 3: Feature Extraction

The model extracts:

- Spatial Features
- Temporal Features
- Frequency Band Information

using deep learning techniques inspired by EEGNet architectures.

---

### Step 4: Multi-Task Classification

A single model simultaneously performs:

1. Communication Intent Classification
2. Emotion Recognition
3. Pain Severity Assessment

This eliminates the need for separate models.

---

### Step 5: Assistive Output Generation

The classified outputs are translated into meaningful information for:

- Patients
- Caregivers
- Healthcare Professionals

---

## 📊 Datasets Used

The system utilizes publicly available EEG datasets:

### KARA One Dataset

Used for:

- Communication Intent Detection
- Imagined Speech Analysis

### SEED-IV Dataset

Used for:

- Emotion Recognition

### PainMonit Dataset

Used for:

- Pain Severity Detection

---

## 🤖 Deep Learning Model

The framework uses an EEGNet-inspired Deep Learning architecture.

### Components

- Temporal Convolution Layers
- Spatial Filtering Layers
- Separable Convolutions
- Batch Normalization
- Dropout Layers
- Dense Classification Layers

---

## 📈 Experimental Results

### Classification Accuracy

| Task | Accuracy |
|--------|----------|
| Intent Detection | 86% |
| Pain Detection | 92% |
| Emotion Recognition | 90% |
| Overall System Accuracy | 89% |

### Precision, Recall & F1-Score

| Task | Precision | Recall | F1 Score |
|--------|----------|--------|----------|
| Intent | 0.86 | 0.85 | 0.85 |
| Pain | 0.92 | 0.91 | 0.91 |
| Emotion | 0.90 | 0.89 | 0.89 |

---

## 🛠 Technology Stack

### Programming Languages

- Python

### Deep Learning

- TensorFlow
- Keras

### Data Processing

- NumPy
- Pandas
- SciPy

### Visualization

- Matplotlib
- Seaborn

### EEG Processing

- MNE-Python

### Machine Learning

- Scikit-Learn

---

## 💡 Applications

### Healthcare

- Assistive Communication
- Remote Patient Monitoring
- Pain Assessment

### Rehabilitation

- Neuro-Rehabilitation
- Brain-Computer Interfaces

### Smart Healthcare

- Real-Time Monitoring
- Caregiver Support Systems

---

## 🔮 Future Scope

- Real-Time EEG Device Integration
- Personalized Adaptive Learning
- Transformer-Based EEG Models
- Mobile Application Deployment
- Hospital Monitoring Integration
- Smart Wheelchair Control
- Voice Generation from EEG Signals

---

## 📂 Repository Note

Due to the large size of EEG datasets, trained deep learning models, preprocessing files, and experimental resources, some project files are not included in this GitHub repository.

The repository contains the core implementation, research methodology, and documentation necessary to understand and reproduce the project.

For complete project resources, datasets, trained models, or academic collaboration:

📧 devak9391@gmail.com

---

## 👨‍💻 Author

Devakumar A

B.Tech Computer Science and Engineering

Rajiv Gandhi College of Engineering and Technology, Puducherry

Scopus Published Researcher

ORCID: https://orcid.org/0009-0003-8934-6744

---

## 📜 Citation

If you use this work in your research, please cite:

Suresh Kumar RG, Devakumar A, Joseph RV, Sivasubramanian J.

Deep Learning-Based EEG Communication Aid for Paralyzed Patients.

International Journal of Drug Delivery Technology, 2026.

DOI: 10.25258/IJDDT.16.58S.21

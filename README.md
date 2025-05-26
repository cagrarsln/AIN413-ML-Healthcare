# Vibration-Based Feedback for Environmental Sound Recognition – AIN413 Project

This project proposes a mobile-compatible system that listens to environmental sounds and provides haptic feedback for individuals with hearing impairments. The system leverages machine learning for sound classification and translates detected events into vibrations and text-based notifications.

## 📚 Course Info
- Course: AIN413 – Machine Learning for Healthcare
- Semester: 2023–2024 Spring
- Students: Yüksel Çağrı Arslan, Mustafa Eren Cen

## 🧠 Problem Definition

People with hearing loss may not be aware of critical sounds like alarms, car horns, or doorbells. This system bridges that gap by converting audio cues into touch-based feedback and mobile alerts.

## 🔊 Dataset

- **ESC-50 Dataset**: 2,000 audio clips across 50 environmental sound categories (e.g., siren, thunder, dog bark).
- Data is preprocessed into log-mel spectrograms or MFCCs for model training.

## 🧪 Methodology

- **Preprocessing**: Convert raw audio to MFCC/log-mel features
- **Modeling**: Train a machine learning classifier on ESC-50
- **Real-Time Use**: Predict live microphone input on mobile
- **Feedback Layer**:
  - Distinct vibration patterns per sound class
  - Mobile notifications: "Baby is crying", "Doorbell is ringing"
  - (Optional) Visual indicators for children

## ⚙️ Technologies

- Python, Jupyter Notebook
- librosa, scikit-learn / TensorFlow or PyTorch (model-dependent)
- Mobile device integration planned for future versions

## 📎 Files

- `AIN413-Sound-Recognition-With-Haptics.ipynb` – Implementation notebook
- `technical_report.pdf` – Project proposal document


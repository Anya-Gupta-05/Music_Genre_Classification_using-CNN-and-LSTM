# 🎶 Music Genre Classification using CNN & LSTM

## 📌 Overview
This project performs music genre classification using the **GTZAN dataset**, which includes 10 genres with 100 audio files each. Two separate deep learning models were built to explore different input modalities:

- 🖼️ **CNN Model** – Trained on spectrogram images generated from audio files.
- 🎧 **LSTM Model** – Trained on sequential audio features (MFCCs and more).

---

## 📁 Dataset

- **Name:** GTZAN Music Genre Dataset  
- **Structure:** 10 genres (`rock`, `pop`, `jazz`, `classical`, etc.), 100 audio files per genre  
- **Format:** `.wav` files, each 30 seconds long

---

## 🧠 Model Architectures

### 🖼️ CNN Model (Image-Based)
- Converts audio into **mel spectrogram images**
- Uses a Convolutional Neural Network to learn spatial frequency patterns
- Input: 128×128 grayscale spectrogram images

### 🎧 LSTM Model (Audio Feature-Based)
- Extracts **MFCCs**, **chroma features**, **ZCR**, and **RMS energy**
- Uses Long Short-Term Memory (LSTM) networks to capture temporal dependencies
- Input: Time-series audio feature sequences

---

## 📊 Visuals & Metrics

- Spectrogram image samples
- MFCC feature plots
- Training/validation accuracy & loss graphs
- Confusion matrices for genre prediction

---

## 🛠️ Tools & Libraries

- Python
- TensorFlow / Keras
- Librosa (audio processing)
- Matplotlib / Seaborn (visualizations)
- Google Colab (for training with GPU support)


#🎶 Music Genre Classification (CNN & LSTM Models)
📌 Project Overview
This project aims to classify music tracks into genres using the GTZAN dataset, containing 10 genres with 100 audio files each.

Two separate deep learning models were implemented:

CNN Model: Trained on spectrogram images extracted from audio.

LSTM Model: Trained on MFCC features directly from audio files.

📁 Dataset
Name: GTZAN Music Genre Dataset

Structure: 10 genres (rock, pop, jazz, classical, etc.), 100 files per genre

Format: .wav audio files (30 sec each)

🧠 Model Approaches
🖼️ CNN Model (Image-Based)
Converted audio files into mel spectrogram images

Trained CNN to classify based on visual frequency patterns

🎧 LSTM Model (Audio Feature-Based)
Extracted MFCCs, chroma, ZCR, and other audio features

Trained LSTM to learn time-series patterns across the audio

✅ Output
Both models classify tracks into one of the 10 genres

Accuracy and performance evaluated on validation/test sets

Visuals include spectrograms, training graphs, and confusion matrices

💾 Tools & Libraries
Python, TensorFlow/Keras

Librosa (audio processing)

Matplotlib/Seaborn (visualization)

Google Colab (GPU training)


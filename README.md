# 🗣️ ASR Model for Low-Resource Malvi Language

This project is a capstone research work focused on developing an **Automatic Speech Recognition (ASR)** system for the **Malvi language**, a low-resource regional language spoken in parts of India. The goal is to improve accessibility and digital inclusion for Malvi speakers using modern deep learning techniques.

## 📌 Project Objectives

- Build an end-to-end ASR model tailored for Malvi.
- Address challenges of data scarcity in low-resource languages.
- Contribute to the growing field of speech technologies for Indian regional languages.

## 🧠 Key Features

- **Data Collection & Preprocessing**  
  Curated Malvi audio-text pairs and performed audio cleaning, normalization, and alignment.

- **Feature Extraction**  
  Used Mel-Frequency Cepstral Coefficients (MFCCs) and spectrogram features for robust audio representation.

- **Model Architecture**  
  Implemented Deep Learning-based ASR models using:
  - RNNs / BiLSTMs
  - Transformers / Wav2Vec 2.0 (for transfer learning)

- **Training & Evaluation**  
  Trained models on custom datasets and evaluated using metrics like Word Error Rate (WER) and Character Error Rate (CER).

## 🧰 Tech Stack

- **Languages:** Python  
- **Frameworks/Libraries:** PyTorch, TensorFlow, HuggingFace Transformers, torchaudio, librosa  
- **Tools:** Jupyter Notebook, Google Colab, Weights & Biases (W&B), Audacity

## 📁 Dataset
- Custom-built Malvi dataset (open-source or proprietary)
- Preprocessing scripts for audio trimming, sampling rate conversion, and text normalization

# 🗣️ ASR Model for Low-Resource Malvi Language

This project focuses on developing an **Automatic Speech Recognition (ASR)** system for the **Malvi language**, a low-resource Indo-Aryan language spoken in the Malwa region of India. The goal is to contribute to inclusive language technology by building tools that support underrepresented languages.

## 🎯 Objective

To build and train an ASR model that can accurately transcribe spoken Malvi into text, using minimal resources and leveraging transfer learning from pre-trained models.

## 📌 Project Highlights

- 📥 Collected and preprocessed Malvi speech dataset
- 🧠 Trained and fine-tuned models using **Wav2Vec 2.0**
- 🧪 Evaluated performance using **WER (Word Error Rate)**
- 📤 Exported a working model for deployment

## 🧰 Technologies & Tools Used

- **Programming Language:** Python
- **Framework:** PyTorch, Hugging Face Transformers
- **Pre-trained Model:** Facebook's `wav2vec2-large-xlsr-53`
- **Libraries:** 
  - `datasets` (HuggingFace)
  - `transformers`
  - `torchaudio`
  - `jiwer` (for WER calculation)
- **Other Tools:**
  - Google Colab / Jupyter Notebook
  - Audacity (for audio processing)
  - Praat (optional, for phonetic analysis)

## 📁 Dataset

- **Language:** Malvi
- **Data Collected:** Audio recordings of native speakers with transcriptions
- **Format:** `.wav` files (16kHz) and `.txt` transcripts
- **Preprocessing:** Normalization, silence trimming, sampling rate conversion

## 🔧 Model Training Steps

1. **Data Cleaning and Preprocessing**
2. **Tokenization and Feature Extraction**
3. **Fine-tuning Wav2Vec 2.0 on Malvi Dataset**
4. **Evaluation using Word Error Rate (WER)**
5. **Model Saving and Inference Testing**

## 🧠 Key Skills Learned

- Speech data collection and annotation
- Low-resource ASR challenges and strategies
- Fine-tuning transformer models for speech tasks
- Preprocessing audio for machine learning
- Evaluation metrics like WER
- Using Hugging Face and PyTorch for NLP/ASR tasks

## 🚀 Future Improvements

- Expand dataset size and speaker diversity
- Integrate language modeling to improve decoding
- Build a mobile/web app using the ASR model
- Explore multilingual models or multilingual finetuning

## 📂 Project Structure


## 🙋‍♂️ Contributors

-Rakesh Lodhi 
-Manish Meena
-Laxmi Parmar
-Institution: VIT Bhopal
-Mentor: Dr. Anirban Bhowmick
- Course: B.Tech Electronics and Communication Engineering

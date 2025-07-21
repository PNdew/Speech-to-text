# Speech-to-text
# 🇻🇳 Vietnamese Speech Recognition using TensorFlow & Keras

This project implements an end-to-end **Automatic Speech Recognition (ASR)** system for the **Vietnamese language** using deep learning with **TensorFlow** and **Keras**.

##  Features
- Convert spoken Vietnamese audio into text (speech-to-text).
- End-to-end model with Conv1D, BiLSTM, and CTC loss.
- Preprocessing pipeline for audio and text labels.
- Training, evaluation, and inference support.

##  Model Architecture
- 1D Convolutional layers for feature extraction.
- Bidirectional LSTM for sequence modeling.
- Dense layer + CTC (Connectionist Temporal Classification) loss for decoding variable-length sequences.

## Dataset

- Audio files are preprocessed to extract MFCC or spectrogram features.
- Transcripts are normalized and tokenized.

## 🔧 Requirements
- Python 3.x
- TensorFlow 2.xx
- librosa, pandas, NumPy

```bash
pip install tensorflow librosa pandas numpy

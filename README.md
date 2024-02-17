# Emotion-Enhanced-Interview-Chatbot-for-Competency-Assessment-and-Candidate-Preparation

## Overview

The project consists of two main components:

1. **Speech Emotion Recognition:**
   - Utilizes machine learning techniques to recognize emotions from speech audio data.
   - Features are extracted from audio files using the librosa library, and a deep learning model is trained using TensorFlow and Keras.
   - The model predicts the emotional state of the speaker based on the extracted features.

2. **Interview Chatbot:**
   - A chatbot is developed using the Google Palm language model and TensorFlow.
   - The chatbot conducts simulated interviews with candidates and evaluates their responses.
   - Emotion detection is integrated into the chatbot, allowing it to provide feedback based on the emotional expressions detected during the interview.

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- Librosa
- Scikit-learn
- SpeechRecognition
- PyAudio
- Sounddevice

## Usage

1. **Speech Emotion Recognition:**
   - The `extract_features` function extracts features from audio files.
   - The `record_audio` function records audio input from the user.
   - The `convert_audio_text` function converts audio to text using the Google Web Speech API.
   - The `model` predicts the emotional state of the speaker based on the extracted features.

2. **Interview Chatbot:**
   - The chatbot conducts simulated interviews with candidates using the Google Palm language model.
   - The `ConversationChain` class manages the conversation flow and integrates with the Google Palm model.
   - The chatbot records audio input from the user, converts it to text, and generates responses based on the input.

## How to Run

1. Clone the repository: `git clone https://github.com/username/repository.git`
2. Run the notebook: `jupyter notebook`

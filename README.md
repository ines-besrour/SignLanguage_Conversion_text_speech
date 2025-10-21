# SignLanguage_Conversion_text_speech

A deep learning-based project that converts sign language gestures into **text** and **speech**, enabling real-time communication between sign language users and non-signers.

![Sign Language Alphabet](assets\sign_alphabet.jpg)

---

## Project Overview

This project leverages computer vision and deep learning to recognize sign language gestures from a webcam feed. Once a gesture is identified, it is converted into corresponding **text**, and then into **speech** using Python’s `pyttsx3` library.  

The goal is to simulate a real-life dialogue between sign language users and non-signers, providing an accessible communication bridge.

---

## Features

- **Real-Time Gesture Recognition**: Uses your webcam to detect hand gestures.
- **Text Translation**: Recognized gestures are translated into readable text.
- **Text-to-Speech Output**: The translated text is converted into speech with `pyttsx3`.
- **Supports Common Sign Language Alphabets**: Trained on a dataset of basic hand gestures.

---

## Requirements

### Hardware

- Webcam (built-in or USB)

### Software

- **Programming Language**: Python 3.9+
- **Python Libraries**:
  - `OpenCV`
  - `NumPy`
  - `Keras`
  - `TensorFlow`
  - `MediaPipe`
  - `pyttsx3`
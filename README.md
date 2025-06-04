# BLYNK Emotion Recognizer

This project is an emotion recognition system based on real-time **eye-blink detection**, developed using Python and OpenCV. It integrates the **Eye Aspect Ratio (EAR)** algorithm to classify user emotional states such as stress, focus, drowsiness, and excitement.

## 📌 Features

- Real-time emotion detection using webcam input
- Detects eye blinks using facial landmarks
- Classifies emotional states based on blink frequency
- Built with OpenCV and Dlib
- EAR-based blink detection algorithm

## 🛠️ Tech Stack

- Python 3.x
- OpenCV
- Dlib (for facial landmark detection)
- NumPy
- Blynk (optional, for IoT notification extension)

## 🚀 Getting Started
### 1. Clone the Repository
```bash
git clone https://github.com/Roshini-K/Blynk_emotion_recognizer.git
cd Blynk_emotion_recognizer
```

### 2. Install Dependencies
You can use pip to install the required packages:

```bash

pip install -r requirements.txt
```

If requirements.txt isn't available, install manually:
```bash
pip install opencv-python dlib numpy
```

### 3. Run the Script
```bash
python emotion_recognizer.py
```

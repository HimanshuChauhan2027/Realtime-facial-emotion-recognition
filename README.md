# Real-Time Facial Emotion Recognition using CNN

A real-time facial emotion recognition system built with **TensorFlow/Keras**, **OpenCV**, and **Convolutional Neural Networks (CNNs)**. The application captures live video from a webcam, detects human faces using Haar Cascade classifiers, and predicts the displayed emotion in real time.

---

## 📌 Features

- 🎥 Real-time emotion detection using a webcam
- 😀 Detects **7 facial emotions**
- 🧠 CNN-based deep learning model
- 👤 Automatic face detection using OpenCV Haar Cascade
- ⚡ Fast and lightweight inference
- 💾 Pre-trained model included for instant testing
- 📓 Jupyter Notebook provided for model training

---

## 🎯 Detected Emotions

The model classifies facial expressions into the following categories:

- 😠 Angry
- 🤢 Disgust
- 😨 Fear
- 😊 Happy
- 😐 Neutral
- 😢 Sad
- 😲 Surprise

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| TensorFlow / Keras | CNN Model |
| OpenCV | Face Detection & Webcam |
| NumPy | Numerical Operations |
| Jupyter Notebook | Model Training |

---

## 📂 Project Structure

```
Realtime-facial-emotion-recognition/
│
├── Facial Expression Recognition.json     # Model architecture
├── fer.h5                                 # Trained model weights
├── webcam_test.py                         # Real-time emotion detection
├── train_emotion_cnn.ipynb                # Model training notebook
├── haarcascade_frontalface_default.xml    # Face detection model
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Realtime-facial-emotion-recognition.git
cd Realtime-facial-emotion-recognition
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python webcam_test.py
```

Your webcam will open, and the detected emotion will be displayed above the detected face.

---

## 🧠 Model Overview

The project uses a **Convolutional Neural Network (CNN)** trained on grayscale facial images.

### Pipeline

1. Capture video frame
2. Detect face using Haar Cascade
3. Convert face to grayscale
4. Resize to model input dimensions
5. Normalize pixel values
6. Predict emotion using CNN
7. Display emotion label in real time

---

## 📸 Output

The application detects faces from the webcam and overlays the predicted emotion label on the video feed in real time.

Example:

```
😊 Happy
😢 Sad
😠 Angry
😲 Surprise
```

---

## 📋 Requirements

- Python 3.8+
- TensorFlow
- OpenCV
- NumPy
- Webcam

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🚀 Future Improvements

- Improve model accuracy with transfer learning
- Support multiple face detection
- Deploy as a web application using Flask or Streamlit
- Optimize inference speed
- Add emotion confidence scores
- Support video file input

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is intended for educational and research purposes.

---

## 👨‍💻 Author

**HIMANSHU CHAUHAN**

If you found this project useful, consider giving it a ⭐ on GitHub!

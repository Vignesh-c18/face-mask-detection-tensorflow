# Real-Time Face Mask Detection using TensorFlow & Keras

A real-time Face Mask Detection system built using **TensorFlow**, **Keras**, **OpenCV**, and **MobileNetV2**. The application detects human faces from a live webcam feed and classifies each face as **Mask** or **No Mask** using a deep learning model.

---

## Features

- Real-time face detection using OpenCV DNN.
- Face mask classification using MobileNetV2.
- Deep Learning model built with TensorFlow & Keras.
- Live webcam detection with confidence scores.
- Detects multiple faces simultaneously.
- Automatic violation logging for users not wearing masks.
- Simple and easy-to-use interface.

---

## Tech Stack

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- MobileNetV2
- Deep Learning
- Computer Vision

---

## Project Structure

```text
face-mask-detection-tensorflow/
│
├── face_detector/
│   ├── deploy.prototxt
│   └── res10_300x300_ssd_iter_140000.caffemodel
│
├── detect_mask_video.py
├── train_mask_detector.py
├── mask_detector.model
├── requirements.txt
├── plot.png
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Vignesh-c18/face-mask-detection-tensorflow.git
```

Move into the project directory

```bash
cd face-mask-detection-tensorflow
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Project

Start real-time detection

```bash
python detect_mask_video.py
```

Train the model

```bash
python train_mask_detector.py
```

---

## Model Performance

The model was trained using TensorFlow and Keras with MobileNetV2 as the backbone network.

**Training Results**

- Training Accuracy: ~96%
- Validation Accuracy: ~90%
- Low training loss after convergence
- Real-time inference using OpenCV

---

## 📈 Training Graph

<p align="center">
<img src="plot.png" width="650">
</p>

---

## Output

The application performs:

- Face Detection
- Face Mask Classification
- Multiple Face Detection
- Real-Time Webcam Prediction
- Confidence Score Display

---

## Applications

- Offices
- Hospitals
- Educational Institutions
- Public Places
- Airports
- Shopping Malls
- Surveillance Systems

---

## Future Enhancements

- Email/SMS alert system
- Face recognition integration
- Cloud deployment
- Mobile application
- Attendance management
- IoT-based monitoring

---

## Author

**N. Vignesh**

- GitHub: https://github.com/Vignesh-c18
- LinkedIn: https://linkedin.com/in/vigneshn18

---

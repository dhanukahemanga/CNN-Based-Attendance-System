# CNN-Based Face Recognition Attendance System 👨💻📊

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-orange)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-red)
![License](https://img.shields.io/badge/License-MIT-green)

An automated attendance system using facial recognition with Convolutional Neural Networks (CNN). Detects faces in real-time and logs attendance to CSV with timestamps.

## Key Features ✨
- Real-time face detection and recognition
- CNN model trained with ~60% accuracy
- Haar Cascades for face detection preprocessing
- Automatic attendance logging to CSV
- Lightweight and scalable design

## Tech Stack 🛠️
- **Python 3.8+**
- **OpenCV** (for face detection and image processing)
- **TensorFlow/Keras** (CNN model implementation)
- **Pandas** (for attendance records)
- **NumPy** (numerical operations)

## Installation ⚙️
```bash
git clone https://github.com/yourusername/cnn-attendance-system.git
cd cnn-attendance-system
pip install -r requirements.txt

## Project Structure
text
├── dataset/            # Training images
├── models/             # Saved CNN models
├── attendance_records/ # Generated CSV logs
├── train_model.py      # Model training script
├── attendance_system.py # Main application
└── requirements.txt    # Dependencies

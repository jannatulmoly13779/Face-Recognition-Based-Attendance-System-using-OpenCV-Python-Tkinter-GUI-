# 🎯 Face Recognition Attendance System (Python + OpenCV)

An intelligent attendance system that uses **computer vision and machine learning** to automatically mark attendance based on facial recognition.

---

## 📌 Overview

This project captures student faces, trains a recognition model, and marks attendance automatically using a webcam.

---

## 🔧 Technologies Used

- Python
- OpenCV (LBPH Face Recognizer)
- Tkinter (GUI)
- NumPy, Pandas
- Haar Cascade Classifier

---

## ⚙️ System Workflow

1. Register Student (ID + Name)
2. Capture Face Images (Dataset Creation)
3. Train Model (LBPH Algorithm)
4. Detect Face via Webcam
5. Recognize Student
6. Mark Attendance (CSV File)

---

## 🧠 Core Functions

### 📸 TakeImages()
- Captures 500 face samples
- Saves images in dataset folder
- Stores ID & Name in CSV

### 🤖 TrainImages()
- Uses LBPH algorithm
- Trains model with captured dataset
- Saves model as `Trainner.yml`

### 🎥 TrackImages()
- Detects faces in real-time
- Matches with trained dataset
- Marks attendance with date & time

---

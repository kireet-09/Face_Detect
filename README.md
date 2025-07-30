# 🧠 Real-Time Face Detection using OpenCV

## 📌 Overview

This project demonstrates real-time face detection using OpenCV’s Haar Cascade Classifier and your system’s webcam. 
It detects human faces and draws rectangles around them live.

## 🛠 Technologies Used

* Python 3
* OpenCV (cv2)
* Haar Cascade Classifier (`haarcascade_frontalface_default.xml`)

## ▶️ How It Works

1. Capture real-time video using webcam.
2. Convert video frames to grayscale.
3. Use Haar Cascade to detect faces.
4. Draw blue rectangles around detected faces.

## 💻 How to Run

1. **Install OpenCV**:

   ```bash
   pip install opencv-python
   ```

2. **Run the script**:

   ```bash
   python face_detection.py
   ```

3. **Exit**:
   Press `q` to quit the program.

## 🧾 File Summary

* `face_detection.py` — Main script
* `README.md` — Project documentation

## 📄 License

Licensed under the **MIT License**.

## 🙌 Credits

* OpenCV for Haar Cascade XMLs
* Developed using Python & OpenCV

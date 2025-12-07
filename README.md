# Face Recognition System – AI Without ML

This project is a real-time **face recognition system** built using **MediaPipe** for face detection and **LBPH (Local Binary Patterns Histogram)** for classical face recognition.

The system demonstrates how **face detection and face recognition work together** in an **AI Without Machine Learning** pipeline.

---

## �� Project Structure

Face_Recognition/
├── dataset_faces/
│ ├── Belyse/
│ └── Gabriella/
├── collect_faces.py
├── face_mesh_test.py
└── ReadMe.md


---

## ⚙️ Technologies Used

- Python
- OpenCV (opencv-contrib-python)
- MediaPipe
- NumPy

---

## ✅ Features

- Real-time face detection using MediaPipe
- Face data collection using webcam
- LBPH classical face recognition
- Multiple person recognition support

---

## Installation

Install the required libraries:

```bash
pip install opencv-contrib-python mediapipe numpy


📸 Step 1: Collect Face Data

This script captures face images and stores them in the dataset.

Run:

python collect_faces.py

You will be asked to enter a name (example: Gabriella or Belyse).


The system will:

-Turn on your webcam
-Detect your face
-Save 100 grayscale face images
-Press Q to stop early


Saved files go to:
dataset_faces/<person_name>/

🧠 Step 2: Train and Recognize Faces

Run the main recognition system:

python face_mesh_test.py


This script:

-Uses MediaPipe to detect faces
-Uses LBPH to recognize faces
-Displays the recognized name in real time
-Press Q to exit the program."# Face_Recognition_Media_Pipe" 
Collapse











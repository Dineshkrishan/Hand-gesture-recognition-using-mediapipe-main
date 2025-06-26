# Hand-gesture-recognition-using-mediapipe-main
✋ Hand Gesture Recognition using MediaPipe
A real-time hand gesture recognition system built using Python, OpenCV, and MediaPipe. This project detects and classifies hand gestures using computer vision and landmark tracking, enabling gesture-based interaction for various applications.

📌 Table of Contents
Overview

Features

Tech Stack

How It Works

Installation

Usage

Applications

Future Enhancements

License

🔍 Overview
This project leverages Google's MediaPipe for accurate hand tracking and landmark detection to recognize static hand gestures. It's suitable for applications like gesture-based control systems, virtual sign language interpreters, and touchless interfaces.

✅ Features
Real-time hand detection using webcam

21-point hand landmark detection

Static gesture recognition using landmark positions

Lightweight and fast performance

Easily extendable for custom gestures

🧰 Tech Stack
Languages: Python

Libraries: MediaPipe, OpenCV, NumPy

Tools: Jupyter Notebook / Python scripts

Version Control: Git, GitHub

⚙️ How It Works
Capture webcam feed using OpenCV

Detect hands and landmarks with MediaPipe

Extract key points (21 landmarks)

Classify gestures based on landmark positions

Display detected gestures in real-time

🚀 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Dineshkrishan/Hand-gesture-recognition-using-mediapipe-main.git
cd hand-gesture-recognition-using-mediapipe-main
Install the required packages:

bash
Copy
Edit
pip install mediapipe opencv-python numpy
🧪 Usage
Run the Python script:

bash
Copy
Edit
python hand_gesture_recognition.py
Make sure your webcam is connected and accessible.

🎯 Applications
Human-computer interaction (HCI)

Smart home gesture control

Virtual gaming interfaces

Sign language recognition

Touchless kiosk interfaces

🔮 Future Enhancements
Add support for dynamic gestures

Integrate gesture-to-action mapping

Export gestures to control external applications (e.g., media player, IoT devices)

Use ML models (e.g., SVM, CNN) for gesture classification

📝 License
This project is licensed under the MIT License.

# StudyAlert – Drowsiness Detection System

StudyAlert is a real-time drowsiness detection system designed to monitor user alertness during study sessions. The system utilizes computer vision techniques to detect signs of eye closure and reduced attention, providing timely warnings to help users stay focused and productive.

This project is built without heavy machine learning models, focusing instead on a lightweight and efficient approach using facial and eye detection combined with Eye Aspect Ratio (EAR) analysis. It is optimized for real-time performance and simplicity, making it suitable for students and developers who want to understand the fundamentals of vision-based alertness systems.

Features
Real-time face and eye detection using webcam
Eye Aspect Ratio (EAR) calculation for drowsiness detection
Popup alert notification when drowsiness is detected
Lightweight implementation without deep learning dependencies
Simple and modular code structure
How It Works

The system captures video input from the webcam and processes each frame to detect the user's face and eyes. It then calculates the Eye Aspect Ratio (EAR) to determine whether the eyes are open or closed.

If the EAR value falls below a predefined threshold for a certain number of consecutive frames, the system classifies the user as drowsy and triggers a popup alert.

Project Structure
StudyAlert-Drowsiness-Detection-System/
|
├── main.py
├── requirements.txt
├── src/
│   ├── detection/
│   ├── core/
│   ├── ui/
├── models/
└── assets/
Requirements
Python 3.x
OpenCV
NumPy

Install dependencies:

pip install -r requirements.txt
Usage

Run the application:

python main.py

Make sure your webcam is enabled. The system will start detecting your face and monitoring your eye state in real-time.

Notes
Detection accuracy may vary depending on lighting conditions
Works best in a well-lit environment with a clear view of the face
Designed for educational and experimental purposes
Future Improvements
Add study session tracking and analytics
Improve detection robustness under different conditions
Integrate a graphical user interface
License

This project is open-source and available for educational use.

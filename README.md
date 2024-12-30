# Physio-Exercise
Our idea uses computer vision with MediaPipe Pose and a Tkinter-based GUI to guide users through squats, providing real-time feedback on posture, reps, and sets. It combines exercise tracking with a user-friendly interface for enhanced fitness experiences.
# physio-Exercise
# Exercise Tracker with Real-Time Feedback

Overview
This project is a physio exercise application that guides users through squats using computer vision and provides real-time feedback on posture, reps, and sets. The application leverages MediaPipe Pose for pose detection and integrates with a Tkinter-based graphical user interface (GUI) to enhance user experience. It offers live feedback to help users maintain proper form and achieve effective workouts.

## Features
Real-Time Posture Detection: Uses MediaPipe Pose to analyze joint angles and detect squat movements.
Repetition and Set Tracking: Automatically counts reps and sets during the workout.
Live Feedback: Provides visual and textual feedback to correct form and motivate users.
User-Friendly Interface: Implements a Tkinter-based GUI for seamless interaction.
Session Summary: Displays completed sets and reps at the end of the session.

## Technologies Used
Python: Programming language for implementing the application.
MediaPipe: Pose detection library for real-time posture analysis.
OpenCV: Library for handling webcam input and image processing.
Tkinter: GUI toolkit for building the user interface.
NumPy: Used for numerical calculations, such as angle computation.

## Installation
1. Clone the repository:
   bash
   git clone https://github.com/your-username/exercise-tracker.git
   cd exercise-tracker
   
2. Install required dependencies:
   bash
   pip install -r requirements.txt
   

3. Run the application:
   bash
   python app.py
   

## How It Works
1. Launch the application, and the Tkinter interface will appear.
2. Start the webcam feed for pose detection.
3. Perform squats in front of the camera.
4. The application calculates the angle of key joints and provides feedback to ensure correct posture.
5. Reps and sets are counted automatically, and live feedback is displayed in the GUI.

## Key Functionality

Detects key landmarks like the hip, knee, and ankle to calculate the joint angle.

### Feedback Mechanism
 Displays messages like "Keep it up!" or "Stand tall!" based on the user’s posture.

### Session Statistics
Keeps track of the total sets and reps completed during the session.

## Future Enhancements
Add support for additional exercises.
Include progress tracking and data visualization.
Integrate with mobile platforms for better accessibility.

## Contribution
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

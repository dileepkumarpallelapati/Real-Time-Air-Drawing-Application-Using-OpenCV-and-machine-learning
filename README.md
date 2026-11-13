# Real-Time-Air-Drawing-Application-Using-OpenCV-and-machine-learning
# Real-Time Air Drawing 

## Project Description
Real-Time Air Drawing is a Python-based project that allows users to draw on a virtual canvas using hand movements in front of a webcam.

The project uses MediaPipe to detect hand landmarks and OpenCV to track finger movements and draw different colors on the screen.

## Features
- Real-time hand detection.
- Finger movement tracking.
- Draw using index finger movements.
- Select different colors: Blue, Green, Red, and Yellow.
- Clear the drawing canvas.
- Webcam-based drawing without touching the screen.

## Technologies Used
- **Python** – Main programming language.
- **OpenCV** – Captures webcam video and draws on the canvas.
- **MediaPipe** – Detects and tracks hand landmarks.
- **NumPy** – Creates and manages the drawing canvas.
- **Deque** – Stores drawing points.

## Project Requirements
- Python 3.11 (recommended for compatibility with the legacy MediaPipe Hands API).
- Working webcam.
- Required Python libraries.

## Installation

1. Clone the repository:

   git clone YOUR_GITHUB_REPOSITORY_URL

2. Open the project folder:

   cd Air_app

3. Install the required libraries:

   pip install -r requirements.txt

4. Run the application:

   python app.py

## How to Use
1. Run the Python application.
2. Allow access to your webcam.
3. Show your hand in front of the camera.
4. Use your index finger to draw.
5. Select Blue, Green, Red, or Yellow from the toolbar using your finger.
6. Select Clear to erase the drawing.
7. Press **Q** or **ctrl c** to close the application.

## How It Works
1. OpenCV captures video from the webcam.
2. MediaPipe detects the hand and identifies 21 hand landmarks.
3. The index fingertip coordinates are identified.
4. Python processes the finger movements.
5. OpenCV draws lines on the virtual canvas using the selected color.

## Project Structure

Air_app/
│
├── app.py
├── requirements.txt
└── README.md

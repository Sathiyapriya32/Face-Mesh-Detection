# Face Mesh Detection with MediaPipe and OpenCV

This project utilizes **MediaPipe** and **OpenCV** to detect face landmarks and visualize the face mesh in real-time using a webcam. It supports multi-face detection and displays the landmarks and contours on each detected face.

## Prerequisites

Make sure you have the following dependencies installed:

- Python 3.x
- `opencv-python`
- `mediapipe`

You can install the required libraries using the following command:

```bash
pip install opencv-python mediapipe
```

## Code Overview
1. Imports:
We import OpenCV, MediaPipe, and other necessary libraries to capture video, detect face landmarks, and display the results.

2. Face Mesh Setup:
We initialize MediaPipe Face Mesh solution and create a face_mesh object with parameters to detect up to 5 faces and a minimum detection confidence of 0.5.

3. Main Loop:
The code continuously captures frames from the webcam, processes them to detect face landmarks, and then visualizes the face mesh on each detected face.

Face Landmark Detection: The program detects the landmarks of each face in the webcam feed.

Face Mesh Visualization: The detected landmarks are drawn on the frame, and the contours between landmarks are connected to visualize the mesh.

Mirror Effect: The video feed is flipped horizontally for a natural "selfie" view.

Exit: Press 'q' to stop the webcam feed and exit the program.

4. Exit:
To exit the program, press the 'q' key.

## How to Run the Code
To run the script, execute the following command:

bash
Copy
Edit
python FaceMesh.py
Usage
Start the webcam: The program will start capturing the video feed from your webcam.

Face Mesh Detection: The program detects face landmarks and connects them to form a mesh for each detected face.

Exit: Press the 'q' key to stop the webcam feed and close the application.

##  📸Screenshots
![Screenshot 2025-04-27 at 1 32 07 PM](https://github.com/user-attachments/assets/18f2d6aa-aed4-4a36-9f85-68a0953aa3fb)


# Face Recognition Attendance System

This Python project utilizes the `face_recognition` library and `cv2` (OpenCV) to build a face recognition attendance system. The system can detect and recognize faces in images or live video streams, and automatically mark attendance in a CSV file.

## Features

- Face detection and recognition using the `face_recognition` library.
- Real-time face recognition from a webcam or video feed.
- Automatic attendance marking in a CSV file.
- Configurable parameters for face detection and recognition.

## Requirements

- Python 3.0 and above
  
## Usage

1. Prepare a dataset of images representing the faces of individuals whose attendance you want to track.
2. Train the face recognition model on the dataset using the provided script.
3. Run the main script to start the face recognition attendance system.
4. The system will detect and recognize faces, and mark the attendance of recognized individuals in a CSV file.

# Output

<img width="973" alt="Screenshot 2023-07-09 at 2 40 27 PM" src="https://github.com/Hazzerback25/Face-Recognition-Attendance-Project/assets/85587494/8871df2d-f1d5-4f15-8902-f787443808b3">

<img width="970" alt="Screenshot 2023-07-09 at 2 39 39 PM" src="https://github.com/Hazzerback25/Face-Recognition-Attendance-Project/assets/85587494/23bed59b-9fe8-4bb8-af77-baa592521ac6">

<div align="center">
  <img width="158" alt="Screenshot 2023-07-09 at 2 51 06 PM" src="https://github.com/Hazzerback25/Face-Recognition-Attendance-Project/assets/85587494/9cc7f33d-9e68-44e2-87c2-ce2146dba31f">
</div>


## Configuration

You can modify various parameters and settings in the configuration file (`config.py`) to adjust the behavior of the system. These include:

- Face detection and recognition thresholds.
- File paths for the dataset, trained models, and attendance CSV file.
- Webcam/video feed settings.


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

## Configuration

You can modify various parameters and settings in the configuration file (`config.py`) to adjust the behavior of the system. These include:

- Face detection and recognition thresholds.
- File paths for the dataset, trained models, and attendance CSV file.
- Webcam/video feed settings.


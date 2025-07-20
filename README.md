# Face Recognition System

This project implements a real-time Face Recognition system using OpenCV and a K-Nearest Neighbors (KNN) classifier. It was developed during my internship at NoviTech, under the mentorship of Mr. T. Muthuvel Ramesh.

## Project Overview

The goal was to build a system that could recognize known faces from a webcam feed and label unknown individuals as "Unknown Person." The model was trained using a custom image dataset.

## Test Case Results

- **Input:** Steve  
  **Output:** Steve  
  (Steve's image was included in the training dataset.)

- **Input:** Kalpana  
  **Output:** Unknown Person  
  (Kalpana's image was not part of the training data.)

This confirmed that the system successfully recognizes trained faces while identifying unfamiliar ones as unknown.

## Key Features

- Real-time face detection and recognition from webcam
- Uses Haar Cascades for face detection
- Trained with labeled face images
- Classifies unknown faces correctly
- Simple and efficient implementation with KNN

## Technologies Used

- Python
- OpenCV
- NumPy
- scikit-learn (KNeighborsClassifier)


## Installation

Install required packages:

```bash
pip install opencv-python scikit-learn numpy




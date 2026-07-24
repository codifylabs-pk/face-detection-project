# Face Detection Project

Face detection using OpenCV and LBF facemark model. This project detects faces in images and extracts the eyes and nose region using facial landmarks.

## Features
- Detects faces from images using Haar Cascade Classifier
- Extracts facial landmarks (68 points) using LBF Facemark model
- Crops and saves left eye, right eye, and nose separately for each detected face

## Requirements
- Python
- OpenCV (opencv-contrib-python)
- NumPy

## How to Use
1. Place your input images inside the `images` folder
2. Run the notebook `face detection 2.ipynb`
3. Detected faces, eyes, and nose crops will be saved inside the `detected_faces` folder

## Files
- `face detection 2.ipynb` — Main notebook with the face detection code
- `lbfmodel.yaml` — Pre-trained LBF facemark model used for landmark detection# face-detection-project
Face detection using OpenCV and LBF facemark model to detect faces, eyes, and nose from images.

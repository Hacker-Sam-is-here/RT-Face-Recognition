# Real-Time Face Recognition System

This project implements a real-time face recognition system using Python and OpenCV. It includes scripts for face detection, model training, and real-time recognition.

## Project Overview

The system uses a Haar cascade classifier for face detection and a custom-trained model for face recognition. The following files are included in the project:

- **`Face recognition.py`**: The main script for running real-time face recognition. This script captures video from the webcam, detects faces, and identifies them using the trained model.
- **`haarcascade_frontalface_default.xml`**: An XML file containing the Haar cascade classifier for detecting frontal faces. This file is used by OpenCV for face detection.
- **`Model Trainer.py`**: A script for training the face recognition model. This script takes sample images of faces and trains a model that can be used for recognition.
- **`Sample generator.py`**: A script for generating sample images of faces. This script captures images from the webcam and saves them to the `samples/` directory.
- **`samples/`**: A directory containing sample images of faces used for training the model.
- **`trainer/`**: A directory containing the trained face recognition model.

## How to Use

1.  **Generate Sample Images**: Run `Sample generator.py` to capture sample images of faces.
2.  **Train the Model**: Run `Model Trainer.py` to train the face recognition model using the sample images.
3.  **Run Face Recognition**: Run `Face recognition.py` to start real-time face recognition.

## Dependencies

-   Python 3.x
-   OpenCV
-   numpy

## Notes

-   Ensure that you have the required dependencies installed before running the scripts.
-   The accuracy of the face recognition system depends on the quality and quantity of the sample images used for training.

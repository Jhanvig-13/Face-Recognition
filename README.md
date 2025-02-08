# Face Recognition

## Overview

This project implements a face recognition system using OpenCV and the Haarcascade dataset. It involves capturing live video, extracting faces, training a recognition model, and testing it against new input data.

## Features

- Live video capture from a webcam

- Face detection using Haarcascade

- Image storage for training

- Model training for face recognition

- Testing the trained model with unknown data 

## Installation & Implementation  

- **Setup Environment**  
   1. Install [Anaconda](https://www.anaconda.com/) and required libraries:  
     ```bash
     pip install opencv-python
     ```  
   2. Launch Jupyter Notebook from Anaconda Navigator.  

- **Prepare Dataset**  
   1. Download the Haarcascade XML file from [OpenCV GitHub](https://github.com/opencv/opencv).  
   2. Create a project folder and an `images` subfolder to store captured faces.  

- **Capture Face Data**  
   1. Import `cv2` and `os` libraries.  
   2. Access the webcam and take user input (name & ID).  
   3. Detect faces using Haarcascade and store images in the `images` folder.  

- **Train the Model**  
   1. Train a face recognition model using collected face images.  

- **Test & Recognize Faces**  
   1. Run the trained model to recognize faces from new input data.  

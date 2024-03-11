# Head Pose Estimation Project

## Overview

This project aims to estimate the head pose (pitch, yaw, and roll angles) of a person in images or videos using the Mediapipe library for face mesh detection and Regression models for pose prediction.


## Features

- **Face Mesh Detection**: Utilizes the Mediapipe Face Mesh module to detect facial landmarks for accurate head pose estimation.

- **Regression Models**: Employs regression models (EX: linear regression, huber regression, support vector regression..etc) to predict head pose angles based on normalized facial landmarks.

- **Visualization**: Displays the estimated head pose on the input images or videos.

## Prerequisites

Make sure you have the following dependencies installed:

- Python 3
- OpenCV
- Mediapipe
- Scikit-learn
- numpy
- pandas

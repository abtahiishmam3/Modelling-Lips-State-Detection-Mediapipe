# Modelling-Lips-State-Detection-Mediapipe
This repository contains code implementing a lips state detection and classifier model powered by mediapipe - google's state of the art CNN and was inspired by the techniques outlined in our paper titled "Modelling Lips State Detection Using CNN for Non-verbal Communications"


## Overview
The primary goal of this project is to detect and classify different states of the lips using advanced computer vision techniques and deep learning. The model leverages the capabilities of MediaPipe for robust facial landmark detection and incorporates the landmark information into a GridSearchCV optimized Support Vector Classifier for accurate lips state classification. The proposed solution delineates solutions that can be applied in non-verbal communication analysis.

## Features
### Lips State Detection
Accurate detection of lip features through facial landmark analysis using MediaPipe.

### Real-time Application
Includes functions for realtime application and classification.

### Classifier Model
A grid search optimized Support Vector Classifier Model for classifying different lips states with examples of training and applications.

### Inspired by Research
Our approach is grounded in research, as detailed in the paper "Modelling Lips State Detection Using CNN for Non-verbal Communications."

## Dependencies
Make sure to install the required dependencies before running the code. You can find them in the requirements.txt file.

conda create --name <env> --file requirements.txt 

## Usage
Clone the repository: git clone https://github.com/abtahiishmam3/Modelling-Lips-State-Detection-Mediapipe.git

Navigate to the project directory: cd Modelling-Lips-State-Detection-Mediapipe

Run the main notebook: Modelling-Lips-State-Detection-Mediapipe.ipynb

## How to Cite
If you find this work useful in your research, please consider citing our paper.

Ishmam, A., Hasan, M., Hassan Onim, M.S., Roy, K., Hoque Akif, M.A., Nyeem, H. (2022). Modelling Lips State Detection Using CNN for Non-verbal Communications. In: Hossain, S., Hossain, M.S., Kaiser, M.S., Majumder, S.P., Ray, K. (eds) Proceedings of International Conference on Fourth Industrial Revolution and Beyond 2021 . Lecture Notes in Networks and Systems, vol 437. Springer, Singapore. https://doi.org/10.1007/978-981-19-2445-3_5

## Contributing
We welcome contributions from the community! If you would like to contribute to this project, please follow our contribution guidelines.

## License 
This project is licensed under the MIT License - see the LICENSE file for details. 

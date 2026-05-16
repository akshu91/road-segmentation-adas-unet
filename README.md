# Road Segmentation for ADAS using U-Net

Deep learning-based semantic road segmentation system for Advanced Driver Assistance Systems (ADAS) using the BDD100K autonomous driving dataset.

## Overview

This project implements a U-Net based semantic segmentation model for detecting drivable road regions from real-world driving scenes. The model is trained on the BDD100K dataset using TensorFlow/Keras and performs pixel-wise segmentation for autonomous driving applications.

## Features

* U-Net based semantic segmentation
* Road scene understanding for ADAS
* TensorFlow/Keras implementation
* BDD100K dataset preprocessing pipeline
* Pixel-wise road mask prediction
* IoU-based evaluation
* Segmentation visualization pipeline

## Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib

## Dataset

BDD100K Autonomous Driving Dataset

## Model Architecture

* U-Net Architecture
* Encoder–Decoder Structure
* Convolutional Neural Networks (CNNs)

## Results

* Achieved **95% pixel-wise segmentation accuracy**
* Successfully generated road-mask predictions on driving scenes
* Evaluated using IoU-based segmentation metrics

## Project Workflow

1. Data preprocessing and mask generation
2. Model building using U-Net
3. Training and validation
4. Segmentation prediction
5. Visualization of results

## Future Improvements

* Real-time inference optimization
* Dice Score implementation
* Mobile/edge deployment
* Lane detection integration

## Repository Structure

```bash
├── road_segmentation.ipynb
├── README.md
```

## Author

Akshat Shevde

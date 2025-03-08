# StepSense 👟📲📈
<p align="center">
  <img src="./extras/cover.png" width = "800" height = "400" />
</p>

## Overview
StepSense is a mobile activity recognition system that processes smartphone sensor data to detect and count steps during different activities. The algorithm uses accelerometer and gyroscope data to accurately identify walking patterns and stair climbing motions through a comprehensive data processing pipeline.

## Background
- StepSense was undertaken as part of my [Mobile & Ubiquitous Computing](https://omscs.gatech.edu/cs-7470-mobile-ubiquitous-computing) course at [Georgia Tech](https://omscs.gatech.edu/) 🐝.
- I utilized the [phyphox](https://phyphox.org/download/) app to gather raw sensor data from my phone
- 📝 View my [**Full Report**](https://docs.google.com/document/d/1cAkAZE22iwxLPBbcYhuWtymsFqoxvK5y/edit?usp=sharing&ouid=117646515362456696053&rtpof=true&sd=true).
- 🐍 View my [**Python Notebook**](https://colab.research.google.com/drive/1KJaYBPsacuRYWozHNyUqYoJ9pR9mkmEE?usp=sharing)

## Features
- Accelerometer and gyroscope data fusion for improved accuracy
- Multi-stage data processing pipeline including:
  - Signal filtering and noise reduction
  - Activity segmentation for walking vs. climbing
  - Peak detection for step counting
- Visualization of motion patterns and detected steps
- Adaptive thresholding to accommodate different movement styles

# Implementation Details
- The system implements several signal processing techniques:
  - Vector magnitude calculation for orientation-independent analysis
  - Moving average filtering for noise reduction
  - Z-axis variance analysis for climbing detection
  - Temporal smoothing for consistent segmentation
  - Peak detection algorithms for accurate step counting
 
# Technologies Used
- Python for implementation
- NumPy and SciPy for numerical processing and signal analysis
- Matplotlib for data visualization
- Smartphone accelerometer and gyroscope sensors for data collection

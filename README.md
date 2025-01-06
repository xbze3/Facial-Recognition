# Simple Facial Recognition System

## Overview
A Python-based facial recognition system utilizing the `dlib` and `face_recognition` libraries for real-time face detection and recognition. The project is designed to identify and verify known faces in a live video stream.

## Features
- Real-time face detection.
- Encoding and recognition of known faces.
- Configurable to add or update face data.

## Requirements
- Python 3.9 or higher.
- Required libraries:
  - `dlib`
  - `face_recognition`
  - `numpy`
  - `opencv-python`

## Directory Structure
- The program expects a directory named `faces` to exist in the same directory as the script.
- This directory should contain images of faces you want to recognize, with each file named appropriately for easy identification (e.g., `person_name.jpg`).

## Installation
1. Clone the repository:
  ```
    git clone https://github.com/xbze3/Facial-Recognition.git
    cd Facial_Recognition_System
  ```

## Set up a virtual environment
  ```
    python -m venv env
    source env/bin/activate   # Linux
    env\Scripts\activate      # Mac
  ```

## Usage
  ```
    python main.py
  ```

## Credit
- YouTube Tutorial: [Face Recognition With Python 3.10 Tutorial (Webcam)](https://youtu.be/tl2eEBFEHqM?feature=shared)
#### Node: I kept running into an error while developing and this reply by this GitHub user was exactly what I needed to solve the error
- Thread - [GitHub Error Thread](https://github.com/ageitgey/face_recognition/issues/1548)


# Face Recognition with InsightFace + Flask

A Flask-based face recognition web application using InsightFace and FAISS for face embedding and similarity-based identification.

## Overview

The application accepts a face image and compares it with enrolled face embeddings to return a recognized identity or `Unknown`.

The current example dataset contains images associated with:

- Cristiano Ronaldo
- Lionel Messi

The recognition pipeline can be adapted by replacing the images in `known_faces/` and regenerating the face embedding database.

## Features

- Face detection and recognition from uploaded images
- InsightFace-based face embeddings
- FAISS similarity search
- Flask web interface
- Bootstrap-based responsive UI
- Support for JPG, JPEG, and PNG images
- Extendable enrollment workflow

## Project Structure

```text
Face Recognition
├── Face_detection.zip
├── README.md
├── .gitignore
└── Face_detection.zip contents
    ├── known_faces/
    ├── static/
    ├── templates/
    ├── app.py
    ├── enroll.py .py
    ├── rename.py
    ├── verify.py
    ├── git-sync.bat
    └── requirements.txt


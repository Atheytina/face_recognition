# Face Recognition System using Gradio

## Overview
This project implements a real-time **face recognition system** using **Gradio** for the user interface and **deep learning** for face detection and identification.  
The app allows users to upload an image or use a live webcam stream, automatically detecting faces and comparing them with known individuals in the database.

It was designed as a lightweight, interactive web application to demonstrate practical AI deployment using Python.

---

## Features
- Face detection and recognition from images or webcam  
- Interactive Gradio web interface  
- Pre-trained deep learning models for accurate identification  
- Simple database for registering and recognizing known faces  
- Runs locally or can be deployed online (Hugging Face / Colab / localhost)

---

## Technologies Used
- **Python 3.10+**  
- **Gradio** (web interface)  
- **OpenCV** (image handling and display)  
- **face_recognition / dlib** (face encoding and comparison)  
- **NumPy**, **Pillow**

---

## Installation and Setup

### 1. Clone the repository
```bash
git clone https://github.com/Athena-yousra/face-recognition-app.git
cd face-recognition-app

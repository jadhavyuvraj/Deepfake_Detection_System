🛡️ Deepfake Detection System

This project provides a comprehensive toolkit for detecting deepfakes using images, video files, or live webcam feeds. Built with a user-friendly interface and real-time processing, it's designed to help identify manipulated media and raise alerts based on deepfake probability.

🚀 Features
🔹 1. Image Upload from Gallery
Upload an image file and run a deepfake analysis on it.

🔹 2. Video Upload with Live Probability
Upload a video to see frame-by-frame deepfake probability in real time.

🔹 3. Live Webcam Detection
Detect deepfakes from a live webcam feed.

🔹 4. PDF Report Generation
Download a detailed classification report (including metrics and graphs) as a PDF.

🔹 5. Alert Mechanism
A built-in alert system notifies users when deepfake probability exceeds a critical threshold.

🧠 Model & Tech Stack
PyTorch for deep learning model inference

ONNX Runtime for optimized model serving

Timm for pre-trained models

OpenCV for image and video processing

Tkinter for GUI

PIL (Pillow) for image handling

NumPy for numerical operations

PDF generation tools (e.g., matplotlib, reportlab, or similar depending on code)

Project Overview: Real-Time Emotion Recognition

Real-Time Emotion Recognition is a deep learning-based application that detects and classifies facial emotions in real time. Built using Python, OpenCV, TensorFlow, and Streamlit, it enhances user experience by displaying emotion-specific quotes, images, and auditory feedback while tracking emotional trends over time.

Key Features & Implementation Details

Face Detection: Uses OpenCV’s Haar cascade classifier to identify facial regions in a live video feed.
Preprocessing: Converts images to grayscale, resizes (48x48 pixels), and normalizes them for better model performance.
Emotion Classification: A pre-trained CNN model (trained on datasets like FER-2013) predicts emotions in real time.
User Interface: Built using Tkinter & Streamlit, displaying detected emotions alongside motivational quotes & images.
Data Visualization: Tracks emotion frequency and displays insights via Matplotlib bar charts.
Audio Feedback: Uses Pyttsx3 to read motivational quotes aloud, enriching user engagement.

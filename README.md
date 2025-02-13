# Real-Time Emotion Recognition

## Overview
Real-Time Emotion Recognition is a deep learning-based application that detects and classifies facial emotions in real time. Built using **Python, OpenCV, TensorFlow, and Streamlit**, the project enhances user engagement by displaying **emotion-specific quotes, images, and auditory feedback** while tracking emotional trends over time.

## Features
- **Face Detection**: Utilizes OpenCV’s Haar cascade classifier to identify facial regions in a live video feed.
- **Preprocessing**: Converts images to grayscale, resizes them to **48x48 pixels**, and normalizes for improved model performance.
- **Emotion Classification**: Trained on emotion dataset from kaggle, predicts emotions in real time.
- **User Interface**: Built using **Tkinter & Streamlit**, displaying detected emotions alongside **motivational quotes & images**.
- **Data Visualization**: Tracks **emotion frequency** and displays insights using **Matplotlib bar charts**.
- **Audio Feedback**: Uses **Pyttsx3** to read motivational quotes aloud, enhancing user interaction.

## Technologies Used
- **Programming Language**: Python
- **Libraries & Frameworks**:
  - OpenCV (Face detection & preprocessing)
  - TensorFlow/Keras (Deep Learning model)
  - Streamlit & Tkinter (User Interface)
  - Matplotlib (Data visualization)
  - Pyttsx3 (Text-to-Speech for audio feedback)

## Usage
1. The application captures real-time video and detects faces using OpenCV.
2. The trained **CNN model** classifies emotions such as Happy, Sad, Angry, Neutral, etc.
3. The UI displays the **detected emotion**, an associated **motivational quote & image**.
4. **Audio feedback** reads the quote aloud for enhanced engagement.
5. Emotion statistics are visualized using **Matplotlib bar charts**.

## Model Details
- The CNN model is trained on **Face expression recognition dataset**, a dataset of labeled facial expressions.
- Architecture includes **Convolutional layers, Max pooling layers, Fully connected layers, and Softmax activation** for classification.
- Optimized using **Adam optimizer and Categorical Cross-Entropy loss function**.

## Future Enhancements
- Implement **real-time sentiment tracking** over extended periods.
- Deploy as a **web application** using AWS Lambda & API Gateway.
- Replace Haar cascade with **MTCNN** for improved face detection.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## License
This project is open-source and available under the **MIT License**.

## Contact
For any queries or suggestions, feel free to reach out:
- **Author**: Sai Saranya Mulukutla
- **GitHub**: [saisaranya2005](https://github.com/saisaranya2005)
- **LinkedIn**: [Sai Saranya Mulukutla](https://www.linkedin.com/in/sai-saranya-mulukutla-7681aa278/)

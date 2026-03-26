🎭 Deepfake Detection System using ResNeXt & LSTM

This project focuses on detecting deepfake videos using deep learning techniques. It combines ResNeXt (CNN) for feature extraction and LSTM (RNN) for temporal sequence learning to identify manipulated video content.


🚀 Overview
Detects deepfake videos using AI
Uses transfer learning with pretrained ResNeXt
Extracts frame-level features and processes them using LSTM
Integrated with a Django web application for user interaction

🧠 Methodology
Video is split into frames
Frames are passed through ResNeXt to extract features
Feature vectors are fed into an LSTM network
Model predicts whether the video is real or fake

🛠️ Tech Stack
Python
PyTorch / TensorFlow (depending on your implementation)
OpenCV
Django (for web app)
NumPy

📂 Project Structure
Deepfake_detection_using_deep_learning/
│
├── Django Application/
├── Model Creation/
├── Documentation/

🌐 Web Application
-The Django-based web app allows users to:
Upload a video
Run deepfake detection
View prediction results instantly

📊 System Architecture

🔮 Future Improvements
Improve model accuracy
Add real-time detection
Deploy on cloud
Optimize performance

👨‍💻 Author:
Raj Kumar
GitHub: https://github.com/Razz1214

⭐ If you found this project useful, give it a star!

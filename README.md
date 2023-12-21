# Drowsines Detection using Mediapipe in Python

# Overview
This project demonstrates a Drowsiness Detection web application using Python, the Mediapipe Face Mesh solution pipeline, and Streamlit. It employs the Eye Aspect Ratio (EAR) technique to identify signs of drowsiness in real-time video streams. The application utilizes the streamlit-webrtc library to facilitate the transmission of video/audio streams over the network.

# Features
* Real-time Drowsiness Detection using the Mediapipe Face Mesh solution.
* Eye Aspect Ratio (EAR) technique for assessing drowsiness.
* WebRTC integration for streaming live video and audio.
* Streamlit-based web application for an intuitive user interface.

# Requirements
Ensure you have the required Python libraries installed:
cryptography==38.0.0
pyOpenSSL
aiortc
numpy
pydub
mediapipe
streamlit==1.13.0
streamlit_webrtc==0.43.4
streamlit-nested-layout==0.1.1
altair<5

# Usage
1. Run the application:
```python
streamlit run app.py
```
3. Open the provided URL in your web browser.

4. Allow access to your camera.

5. Experience real-time drowsiness detection.

# How it Works
The application utilizes the Mediapipe Face Mesh solution to detect eye landmarks in the video stream. The Eye Aspect Ratio (EAR) is calculated by measuring the relative distances between specific landmarks, providing a metric for assessing drowsiness. If the EAR falls below a predefined threshold, the system triggers a drowsiness alert using an alarm.

# Acknowledgments
This project relies on the following technologies:

* Mediapipe
* Streamlit
* streamlit-webrtc

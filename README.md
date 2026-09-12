
# CrowdLens – AI-Based Crowd Behavior Analyzer

CrowdLens is a backend system designed to analyze crowd behavior from video input using artificial intelligence. It detects anomalies such as sudden increases in crowd density, aggression, or physical altercations that may lead to stampede-prone situations. This project aims to support public safety monitoring systems in real-time environments.

## Features

- Detects crowd count from video frames
- Identifies signs of aggression or fighting (planned)
- Logs analysis data to a CSV file with timestamps
- Structured backend using Flask
- API-based design for integration with frontend dashboards

## Project Structure

CrowdLens/
│
├── app.py
├── crowd_detection.py
├── requirements.txt
├── README.md
│
├── models/
│   └── ...
│
├── input/
    └── crowd_video.mp4

##How the system works

Video Input
     ↓
Frame Extraction using OpenCV
     ↓
Crowd Detection / Person Detection
     ↓
Count People in Each Frame
     ↓
Analyze Crowd Density / Changes
     ↓
Detect Potential Anomalies
     ↓
Store Results with Timestamp
     ↓
CSV / Flask API
     ↓
Frontend Dashboard



Technologies Used
Python – Core programming language
OpenCV – Video processing and frame extraction
Machine Learning / Deep Learning – Person and crowd behavior detection
Flask – Backend REST API
Pandas / CSV – Storing and processing analysis results



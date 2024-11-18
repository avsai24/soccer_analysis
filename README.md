# Soccer Analysis Project

## Introduction
The goal of this project was to develop an advanced Soccer match analysis system capable of detecting and tracking players, referees, and soccer balls in real-time video footage. By leveraging YOLO (You Only Look Once), one of the best AI object detection models available, I was able to track the objects and detect them with high accuracy. Additionally, I implemented a K-Means clustering technique to assign players to teams based on the colors of their t-shirts. This was done through pixel segmentation and clustering to effectively identify and categorize players into their respective teams.

Once the players were identified, the system calculated the ball acquisition percentage for each team, providing insights into which team had control over the ball throughout the match. To accurately measure player movement, I used optical flow techniques to capture camera movements between frames, and perspective transformation to represent the depth and perspective of the scene. This allowed me to measure player movement in meters rather than just pixels, providing a more accurate representation of the distance covered. Finally, I calculated player speed and distance traveled during the match.

This project integrates multiple advanced techniques and tools in computer vision, machine learning, and data processing, making it a comprehensive solution for soccer match analysis.

![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=sharing)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas

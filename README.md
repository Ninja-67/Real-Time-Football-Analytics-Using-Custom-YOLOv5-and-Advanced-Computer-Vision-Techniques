# Football Analysis Project

## Introduction
This project focuses on detecting and tracking players, referees, and footballs in a video using the YOLO object detection model. The project includes training the model to enhance its performance. It involves assigning players to teams based on their t-shirt colors through K-means clustering and pixel segmentation. Optical flow will be used to track camera movement between frames, which aids in accurately measuring player movement. Perspective transformation will be applied to account for depth and perspective in the scene, allowing for measurements in meters rather than pixels. The project will also calculate players' speed and the distance they cover.

![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1yFaZBdlprprkTfxmtTBptWl0g-Kt1FsD/view?usp=sharing)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/17e2rqqEDuCCi8kxtM2v6870uOq3nfGh_/view?usp=sharing)

## Sample output-video
- [Sample output video](https://drive.google.com/file/d/1clT8739HhRnC5lzMkgMdIlP1fPI3t1Aw/view?usp=sharing)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas
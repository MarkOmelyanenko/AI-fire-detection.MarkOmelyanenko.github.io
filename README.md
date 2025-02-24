# Fire Detection and Localization

## Project Overview
This project aims to develop a deep learning-based system for detecting and localizing fire and smoke in images and videos. It leverages pre-trained neural network architectures to perform both image classification and object localization. The system is designed to assist in real-time fire monitoring and early detection using AI techniques.

## Features
- **Image Classification**: Classifies images into three categories – `fire`, `no fire`, and `smoke`.
- **Object Localization**: Identifies the precise location of fire and smoke in an image using bounding boxes.
- **Real-Time Processing**: Analyzes video streams in real-time to detect fire.
- **Explainable AI (XAI)**: Provides interpretability using heatmaps to highlight critical decision areas.

## Technologies Used
- **Python**
- **PyTorch & PyTorch Lightning**
- **OpenCV**
- **Google Colab**
- **VGG16 for Classification**
- **YOLOv8 for Localization**

## Dataset
Three annotated datasets (DB1, DB2, and DB3) were used, containing images labeled as `fire`, `no fire`, and `smoke`. After evaluation, the DB3 dataset was found to yield the best performance.

## Model Development
### 1. Image Classification
- **Architecture**: VGG16
- **Training**: Conducted on Google Colab with GPUs.
- **Performance**: Achieved high accuracy with proper parameter tuning.

### 2. Fire and Smoke Localization
- **Architecture**: YOLOv8 (yolo8s model)
- **Output**: Bounding boxes around detected fire and smoke in images and videos.

### 3. Explainability (XAI)
- Used **torch-explain** to generate attention heatmaps highlighting important regions in images.

## Examples of Usage
### Videos
[Watch Fire Detection Usage](https://github.com/MarkOmelyanenko/AI-fire-detection.MarkOmelyanenko.github.io/tree/main/Videos)

### Screenshots
![Screenshot 1](https://github.com/MarkOmelyanenko/AI-fire-detection.MarkOmelyanenko.github.io/blob/main/screenshots/screenshot_1.png)
![Screenshot 2](https://github.com/MarkOmelyanenko/AI-fire-detection.MarkOmelyanenko.github.io/blob/main/screenshots/screenshot_2.png)
![Screenshot 3](https://github.com/MarkOmelyanenko/AI-fire-detection.MarkOmelyanenko.github.io/blob/main/screenshots/screenshot_3.png)
![Screenshot 4](https://github.com/MarkOmelyanenko/AI-fire-detection.MarkOmelyanenko.github.io/blob/main/screenshots/screenshot_4.png)
![Screenshot 5](https://github.com/MarkOmelyanenko/AI-fire-detection.MarkOmelyanenko.github.io/blob/main/screenshots/screenshot_5.png)

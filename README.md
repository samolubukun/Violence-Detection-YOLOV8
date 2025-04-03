# Violence Detection using YOLOv8

## Overview
This project implements a YOLOv8-based object detection model trained to detect acts of violence in images and videos. The model is trained using the [Smart Schools Using AI and IOT Dataset]([https://universe.roboflow.com/ds/3cUl9dgLas?key=WKeQTMC4Sl](https://universe.roboflow.com/project-hw9bc/smart-schools-using-ai-and-iot3)) from Roboflow. A **Gradio** interface is integrated for easy interaction, allowing users to upload images or videos for real-time violence detection.
This project implements a YOLOv8-based object detection model trained to detect acts of violence in images and videos. The model is trained using the [Violence Detection Dataset]() from Roboflow. A **Gradio** interface is integrated for easy interaction, allowing users to upload images or videos for real-time violence detection.

## Screenshots
### Image Detection
![Screenshot (368)](https://github.com/user-attachments/assets/64e8b23e-573f-496c-a75e-61c649a24bed)

### Video Detection

https://github.com/user-attachments/assets/dcc30683-2426-4b29-9c94-0df6410247e9

## Features
- **Real-time Image and Video Detection**: Identifies violent activities in both images and videos.
- **YOLOv8 Model**: Trained on a specialized dataset for violence detection.
- **Gradio Interface**: Provides an easy-to-use web UI for detection.
- **Live Video Processing**: Processes video files frame by frame to detect violent activities.

## Dataset
The model was trained using the [Smart Schools Using AI and IOT Dataset]([https://universe.roboflow.com/ds/3cUl9dgLas?key=WKeQTMC4Sl](https://universe.roboflow.com/project-hw9bc/smart-schools-using-ai-and-iot3)), which contains labeled images depicting violent actions.

## Usage
### Running the Jupyter Notebook
To run the model and Gradio interface:

1. Open the Jupyter Notebook and run all cells.
2. The Gradio interface will launch, allowing you to upload images and videos for detection.


## Gradio Interface
The project includes a Gradio interface with two tabs:
1. **Image Detection**: Upload an image, and the model will detect violent actions.

## Future Improvements
- **Model Optimization**: Further fine-tuning for higher accuracy and efficiency.
- **Live Camera Feed**: Implementing real-time violence detection using webcam input.
- **Mobile Deployment**: Converting the model into a mobile-friendly application.



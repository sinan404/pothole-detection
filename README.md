Pothole Detection Using YOLO11s

About the Project

This project uses YOLO11s, a deep learning object detection model, to detect potholes in road images.

The model is trained using a pothole image dataset from Roboflow. It learns to identify potholes and locate them using bounding boxes around the detected objects.

Objectives

Detect potholes in road images.

Locate potholes using bounding boxes.

Evaluate model performance using precision, recall, mAP50, and mAP50-95.

Visualize pothole detection results on new images.

Technologies Used

Python

YOLO11s

Ultralytics

PyTorch

Roboflow

Google Colab

OpenCV

Dataset

The dataset is downloaded from Roboflow and contains images divided into three main sets:

Train: Images used to train the model.

Validation: Images used to evaluate the model during training.

Test: Images used to evaluate the trained model on separate data.

The dataset includes annotations that identify potholes and specify their bounding-box coordinates.

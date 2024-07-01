# Football and Basketball Detection using YOLOv5

This project demonstrates the use of YOLOv5 to detect footballs and basketballs in images. YOLOv5 is a state-of-the-art object detection model known for its speed and accuracy.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Training](#training)
- [Results](#results)
- [Requirements](#requirements)
- [Usage](#usage)

## Overview
![image](https://github.com/tyl-99/football-basketball-detector/assets/71328888/7b193242-5e21-4f0b-b31d-5ff96a3ecc1d)


This is a short project to detect footballs and basketballs in images using the YOLOv5 model. The model is trained to accurately identify and locate these sports balls in various images.

## Dataset

The dataset used for this project consists of images containing footballs and basketballs. The images are annotated with bounding boxes around the objects of interest. The dataset is split into training and test sets for model evaluation.

## Model

The model used in this project is YOLOv5, which stands for "You Only Look Once" version 5. YOLOv5 is a popular object detection model known for its real-time performance and high accuracy.

## Training

The YOLOv5 model is trained on the annotated dataset for several epochs. The training process involves optimizing the model to minimize the detection loss, improving its ability to detect footballs and basketballs accurately.

## Results

The model achieves high accuracy in detecting footballs and basketballs in images. The results include bounding boxes around the detected objects, along with confidence scores indicating the likelihood of correct detection.

## Requirements

- Python 3.x
- PyTorch
- YOLOv5
- OpenCV
- numpy

You can install the required packages using the following command:

```bash
pip install torch opencv-python numpy
```

## Usage

To run the notebook and perform object detection, use the following command:

```bash
jupyter notebook FootballDetector.ipynb
```

You can also use the YOLOv5 model to detect footballs and basketballs in your own images by following the steps in the notebook.

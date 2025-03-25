# Anomaly Detection in Surveillance Videos

This project demonstrates real-time object detection in surveillance videos using TensorFlow's Object Detection API with a pre-trained SSD MobileNet V2 model. The system can detect and classify objects in video streams, which can be extended for anomaly detection scenarios.

## Features

- Real-time object detection in video streams
- Uses SSD MobileNet V2 320x320 model trained on COCO dataset
- Visualizes detected objects with bounding boxes and confidence scores
- Configurable detection threshold
- GPU acceleration support

## Prerequisites

- Python 3.7 or higher
- TensorFlow 2.x
- OpenCV
- TensorFlow Object Detection API

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/anomaly-detection-surveillance.git
   cd anomaly-detection-surveillance

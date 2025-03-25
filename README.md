![anomaly_detected](https://github.com/user-attachments/assets/8f299cba-7ed0-4001-a303-3f1104bdf791)


https://github.com/user-attachments/assets/f4862961-60ba-4638-93e1-50d46acf0eee

DEPLOYED LINK (https://alan-srivastava.github.io/Anomaly-Detection-in-Surveillance-Videos/)

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
   git clone https://github.com/your-username/anomaly-detection-surveillance.git
   cd anomaly-detection-surveillance
Install the required packages:

pip install -r requirements.txt
The necessary model files will be automatically downloaded when you first run the script.

Usage
Place your surveillance video file in the project directory (rename it to sample_video_1.mp4 or modify the code to point to your file).

Run the detection script:

python detect_anomalies.py
Press 'q' to quit the video stream.

Customization
To change the detection threshold, modify the min_score_thresh parameter in the visualize_boxes_and_labels_on_image_array function call.

To use a different model, update the MODEL_DATE and MODEL_NAME variables at the top of the script.

You can extend the code to analyze detection patterns over time for anomaly detection.

Extending for Anomaly Detection
This project provides the foundation for building an anomaly detection system. Potential extensions include:

Behavior Analysis: Track object movements over time to detect unusual patterns

Object Counting: Monitor crowd sizes or vehicle counts for abnormal situations

Zone Monitoring: Detect when objects enter restricted areas

Abandoned Objects: Identify stationary objects that remain in place for too long

Model Information
The project uses the ssd_mobilenet_v2_320x320_coco17_tpu-8 model from TensorFlow's Model Zoo. This model provides a good balance between speed and accuracy for real-time applications.

Performance Notes
The system performs best with GPU acceleration

On CPUs, you may need to reduce the input resolution for real-time performance

Frame processing time depends on hardware capabilities

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

### Additional recommendations:

1. Create a `requirements.txt` file with all the dependencies:
tensorflow>=2.0
opencv-python
numpy

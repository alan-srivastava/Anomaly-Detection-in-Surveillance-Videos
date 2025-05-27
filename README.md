🧠 Overview
This project demonstrates real-time object detection in surveillance videos using TensorFlow's Object Detection API with a pre-trained SSD MobileNet V2 model. It forms the foundation for detecting anomalies by identifying unusual patterns in surveillance footage.

![anomaly_detected]
(https://github.com/user-attachments/assets/8f299cba-7ed0-4001-a303-3f1104bdf791)
https://github.com/user-attachments/assets/f4862961-60ba-4638-93e1-50d46acf0eee

✨ Features
🎯 Real-time object detection from video streams

⚙️ Based on SSD MobileNet V2 320x320 (COCO dataset)

🖼️ Bounding boxes & confidence scores overlay

🎚️ Configurable detection threshold

🚀 GPU acceleration support (for better performance)

📦 Tech Stack
Python 3.7+
TensorFlow 2.x
OpenCV
TensorFlow Object Detection API

📥 Installation

Clone the repository

git clone https://github.com/your-username/anomaly-detection-surveillance.git
cd anomaly-detection-surveillance
Install dependencies
pip install -r requirements.txt
✅ The model files are downloaded automatically when the script is first run.

▶️ Usage
Place your video file (e.g. sample_video_1.mp4) in the project directory.

Run the detection script:
python detect_anomalies.py

⚙️ Customization
Change detection threshold
Edit min_score_thresh in visualize_boxes_and_labels_on_image_array(...).

Use another model
Modify MODEL_DATE and MODEL_NAME at the top of detect_anomalies.py.

🔍 Extend for Anomaly Detection

This project can be enhanced to detect anomalies, such as:

🧭 Behavior Analysis: Track object motion for irregular patterns

🔢 Object Counting: Detect crowding or traffic congestion

🚫 Zone Monitoring: Alert when objects enter restricted areas

🎒 Abandoned Object Detection: Identify items left unattended

📚 Model Info
Model: ssd_mobilenet_v2_320x320_coco17_tpu-8
Source: TensorFlow Model Zoo
✅ Balance of speed and accuracy for real-time applications

🚀 Performance Tips
GPU recommended for real-time frame rates

For CPU users, lower input resolution to improve speed

📄 License
Licensed under the MIT License

🤝 Contributing
Got an idea or improvement? Feel free to open an issue or submit a pull request!

📑 requirements.txt
tensorflow>=2.0
opencv-python
numpy

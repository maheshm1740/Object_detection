🎯 Object Recognition and Tracking System
A Python-based application that performs real-time object recognition and tracking using computer vision techniques. This project leverages OpenCV and pre-trained deep learning models to detect and follow objects in video streams or webcam feeds.

📌 Features
✅ Real-time object detection using deep learning models (YOLO, SSD, etc.)
✅ Object tracking using algorithms like CSRT, KCF, or SORT
✅ Supports video input from webcam or file
✅ Bounding boxes with labels and confidence scores
✅ Configurable tracking for specific object classes
✅ Frame-by-frame visualization and video output saving
🧠 Technologies Used
Python 3.x
OpenCV
NumPy
Pretrained object detection models (e.g., YOLOv5, MobileNet SSD)
(Optional) PyTorch / TensorFlow (if using DL-based models)
📁 Project Structure
object-tracking/ │ ├── models/ # Pre-trained model files ├── utils/ # Utility scripts (helpers, drawing functions, etc.) ├── videos/ # Input video samples ├── output/ # Saved output videos ├── main.py # Main script to run detection & tracking ├── tracker.py # Object tracking logic ├── detector.py # Object detection logic ├── requirements.txt # Required Python packages └── README.md # Project documentation

bash Copy Edit

🚀 Getting Started
🔧 Prerequisites
Python 3.7+
pip
📦 Installation
Clone the repository
git clone https://github.com/maheshm1740/object-tracking.git cd object-tracking

Install dependencies
pip install -r requirements.txt ⚙️ Running the Application bash Copy Edit

Run on webcam
python main.py --source 0

Run on video file
python main.py --source videos/sample.mp4 Sample Arguments --source: Input source (default is webcam: 0)

--model: Path to object detection model (optional)

--tracker: Tracking algorithm (e.g., CSRT, KCF, MIL)

--output: Save output video

🖼️ Output Example Bounding boxes with object names and confidence levels drawn in real-time.

🛠️ Supported Tracking Algorithms You can change the tracker in code or via command line:

CSRT (high accuracy)

KCF (fast but less accurate)

MIL

MOSSE

MedianFlow

📌 TODO / Improvements Add support for multiple object classes

Add UI controls (pause, resume, stop)

Integrate more accurate detectors like YOLOv8 or EfficientDet

Evaluate performance across models

🧪 Example Use Cases Autonomous surveillance

Sports player tracking

Object tracking in robotics

Vehicle tracking in traffic videos

🤝 Contributing Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

📄 License This project is licensed under the MIT License - see the LICENSE file for details.

🙋‍♂️ Acknowledgements OpenCV

YOLO by Ultralytics

PyImageSearch tutorials

yaml Copy Edit

Let me know if you want:

YOLO or SSD-specific setup
Custom logo or visuals in the README
A short write-up on how the tracking algorithm is implemented inside your code
About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Releases
No releases published
Create a new release
Packages
No packages published
Publish your first package
Contributors
2
@Mahesh1740
Mahesh1740
@maheshm1740
maheshm1740 Mahesh M
Languages
Python
100.0%
Suggested workflows
Based on your tech stack
SLSA Generic generator logo
SLSA Generic generator
Generate SLSA3 provenance for your existing release workflows
Python application logo
Python application
Create and test a Python application.
Publish Python Package logo
Publish Python Package
Publish a Python Package to PyPI on release.
More workflows
Footer

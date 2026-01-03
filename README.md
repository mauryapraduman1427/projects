# projects
Real-time object detection web application built with Flask, OpenCV, and YOLOv3 supporting live webcam streaming and image-based detection.
🧠 Real-Time Object Detection Web Application

A Flask-based web application that performs real-time object detection using YOLOv3 and OpenCV. The system supports live webcam streaming as well as image uploads, detects multiple objects with confidence scores, and displays results with class-wise colored bounding boxes.

🚀 Features

📹 Real-time object detection using webcam

🖼️ Image upload & detection

🎯 YOLOv3 deep learning model trained on COCO dataset

🔍 Confidence thresholding & Non-Maximum Suppression (NMS)

🎨 Class-wise colored bounding boxes

🌐 Live video streaming via Flask

🔐 Thread-safe detection control

📊 Displays detected object labels and confidence scores

🛠️ Tech Stack

Backend: Python, Flask

Computer Vision: OpenCV, NumPy

Deep Learning Model: YOLOv3

Frontend: HTML, CSS (Flask Templates)

Concurrency: Python Threading

📂 Project Structure
├── app.py
├── yolov3.cfg
├── yolov3.weights
├── coco.names
├── static/
│   └── annotated_image.jpg
├── templates/
│   ├── index.html
│   ├── detected_objects.html
│   └── upload_result.html
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/object-detection-flask.git
cd object-detection-flask

2️⃣ Install Dependencies
pip install flask opencv-python numpy

3️⃣ Download YOLOv3 Files

Place the following files in the project root:

yolov3.weights

yolov3.cfg

coco.names

📌 Download from official YOLO sources.

▶️ How to Run the Application
python app.py


Then open your browser and go to:

http://127.0.0.1:5000/

🧪 Usage
🔴 Start Live Detection

Click Start Detection

Webcam feed starts with real-time object detection

⏹️ Stop Detection

Click Stop Detection

View list of detected objects

📤 Upload Image

Upload an image file

Get annotated image with detected objects

📌 Supported Objects

The model detects 80+ object classes including:

Person, Car, Bus, Truck

Dog, Cat, Horse

Bottle, Chair, Laptop, Mobile

And many more (COCO Dataset)

🧩 Key Implementation Highlights

YOLOv3 inference using cv2.dnn

Real-time streaming via multipart HTTP response

Thread-safe detection state using locks

Secure image upload using Werkzeug

Modular and scalable Flask architecture

📈 Future Enhancements

GPU acceleration (CUDA)

Model upgrade to YOLOv5 / YOLOv8

Object count statistics

Downloadable detection reports

Improved UI with Bootstrap

👨‍💻 Author

Praduman Maurya
Python Developer | Computer Vision Enthusiast

📄 License

This project is licensed under the MIT License.


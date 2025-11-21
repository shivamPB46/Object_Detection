🚗 Vehicle Detection using YOLOv8 (Python)

This project demonstrates vehicle detection in images using YOLOv8, OpenCV, and Matplotlib.
The script loads a pretrained YOLOv8 model, detects vehicles (car, truck, bus, motorbike), draws bounding boxes, and prints a detailed count of each vehicle type.

🔥 Features
✅ YOLOv8 Object Detection

Uses Ultralytics YOLOv8 pretrained on the COCO dataset

Detects vehicles with high accuracy

Supports: car, truck, bus, motorbike

✅ Clean Visualization

Bounding boxes drawn using YOLO’s built-in .plot()

Outputs a clear, annotated image

Displayed using Matplotlib

✅ Automatic Vehicle Counting

Extracts class labels from YOLO detections

Counts each type using Python’s Counter

Prints vehicle-wise count + total count

✅ Simple & Beginner-Friendly

Short, clean code

Easy to run

No complex setup required

🛠️ Technologies Used

Python 3

OpenCV

Ultralytics YOLOv8

Matplotlib

NumPy

cvlib (optional object detection utility)

📦 Setup & Installation
1. Install dependencies
pip install opencv-python numpy matplotlib cvlib ultralytics

2. Download YOLOv8 model

This is done automatically when you run the code:

model = YOLO("yolov8n.pt")

3. Run the script
python vehicle_detection.py

📁 Project Structure
│── vehicle_detection.py
│── cars.webp
│── README.md
└── requirements.txt  (optional)

🖼️ Output Preview

Annotated image with bounding boxes

Console output:

Cars detected: 5
Trucks detected: 1
Buses detected: 0
Motorbikes detected: 2
Total vehicles detected: 8


(Add your own screenshot here)

🔮 Future Enhancements (Optional)

Real-time video detection using webcam

Vehicle tracking across frames (SORT / DeepSORT)

Speed estimation

License plate detection

Export results to Excel/PDF

🤝 Contributing

Pull requests are welcome!
Feel free to report issues or suggest improvements.

📄 License

MIT License

# Object Detection Using MobileNetSSD

## Project Overview

This project demonstrates real-time object detection using OpenCV and the MobileNetSSD deep learning model. The system captures video from a webcam and detects objects present in the frame.

**Note:** This project was provided as a practice project during training/learning purposes. I studied, executed, and understood the implementation to learn object detection concepts.

---

## Technologies Used

* Python
* OpenCV
* NumPy
* Imutils
* MobileNetSSD
* Caffe Model

---

## Project Files

* `main.py` – Main program file
* `MobileNetSSD_deploy.prototxt.txt` – Model architecture file
* `MobileNetSSD_deploy.caffemodel` – Pre-trained model weights

---

## Working of the Project

1. Load the MobileNetSSD model.
2. Start webcam video capture.
3. Read video frames continuously.
4. Convert frames into blob format.
5. Pass the blob to the MobileNetSSD model.
6. Detect objects with confidence scores.
7. Draw bounding boxes around detected objects.
8. Display object labels on the screen.
9. Show the processed video output in real time.

---

## Input

* Live webcam video stream

## Processing

* Object detection using MobileNetSSD deep learning model

## Output

* Detected object name
* Confidence score
* Bounding box around the object

---

## Objects That Can Be Detected

* Person
* Car
* Bus
* Bicycle
* Dog
* Cat
* Horse
* Chair
* Bottle
* Train
* TV Monitor
* And other MobileNetSSD supported objects

---

## Learning Outcomes

Through this project, I learned:

* Basics of Computer Vision
* Real-time Object Detection
* OpenCV implementation
* Deep Learning model integration
* Webcam video processing
* Bounding box visualization

---

## How to Run

Install required libraries:

```bash
pip install opencv-python
pip install numpy
pip install imutils
```

Run the program:

```bash
python main.py
```

---

## Author

Vaishnavi

Project uploaded for learning and practice purposes.

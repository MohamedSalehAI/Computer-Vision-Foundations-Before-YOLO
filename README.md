# Computer Vision Course & Portfolio

A practical collection of **Computer Vision, Image Processing, Machine Learning, Deep Learning, OCR, Object Detection, Tracking, and MediaPipe** implementations developed during my Computer Vision learning journey.

The repository contains both fundamental Computer Vision techniques and real-time applications using Python and OpenCV-based frameworks.

## 🎯 Purpose

The main purpose of this repository is to document my practical development in Computer Vision and build a structured reference of the techniques and projects I have implemented.

The repository focuses on:

* Image Processing
* Computer Vision fundamentals
* OpenCV
* Image and video processing
* Object detection
* Object tracking
* Face detection and landmarks
* OCR and text recognition
* Image classification
* Image segmentation
* Camera calibration
* Distance estimation
* Feature detection and matching
* MediaPipe
* Real-time Computer Vision applications

## 🛠️ Technologies

### Programming

* Python
* Jupyter Notebook

### Computer Vision

* OpenCV
* OpenCV-Contrib
* MediaPipe
* Pillow

### Machine Learning

* Scikit-learn
* Random Forest
* Image classification
* Clustering

### Deep Learning

* TensorFlow
* Keras
* MobileNet
* MobileNetV2

### OCR

* Tesseract OCR
* Keras-OCR
* PaddleOCR

### Other Tools

* NumPy
* Matplotlib
* Selenium

## 📚 Topics Covered

### 1. OpenCV & Image Processing

Practical implementations covering:

* Image loading and visualization
* Brightness manipulation
* Image resizing
* Geometric transformations
* Drawing and annotations
* Mouse events
* Trackbars
* Bitwise operations
* Thresholding
* Adaptive thresholding
* Morphological operations
* Image smoothing and blurring
* Edge detection
* Image pyramids
* Image blending
* Contours
* Histograms
* OTSU thresholding
* Template matching

### 2. Object Detection

Implementations involving:

* Classical object detection
* Haar Cascade classifiers
* Geometric object detection
* Face detection
* Object detection using OpenCV
* YOLO-based object detection

### 3. Object Tracking

Practical implementations of:

* Single-object tracking
* Multiple-object tracking
* Motion detection
* Background subtraction
* MeanShift
* CamShift

### 4. Face & Landmark Detection

Projects and experiments involving:

* Haar Cascade face detection
* Eye detection
* Eye motion tracking
* Facial landmarks
* Face Mesh
* Drowsiness detection
* Real-time facial analysis

### 5. OCR & Text Recognition

Implementations using:

* Tesseract
* Keras-OCR
* PaddleOCR
* Text detection
* Text recognition
* Arabic text processing
* OCR-based applications

### 6. Image Classification

Topics include:

* Feature-based classification
* Texture classification
* MobileNet
* MobileNetV2
* Transfer learning
* Image augmentation
* Classification pipelines

### 7. Image Segmentation

Implementations involving:

* OTSU segmentation
* K-Means image segmentation
* Background separation
* Foreground/background processing

### 8. Camera Geometry

Practical work involving:

* Camera calibration
* Perspective transformation
* Distance estimation
* Pixel-to-real-world measurements
* Camera geometry

### 9. MediaPipe

Real-time Computer Vision applications using MediaPipe:

* Hand landmark detection
* Hand tracking
* Virtual mouse
* Pose estimation
* Human pose extraction
* Face Mesh
* Holistic tracking
* 3D pose estimation
* Gesture recognition
* Volume control using hand gestures

## 🚀 Practical Projects

Selected practical applications from the repository include:

### ✋ Real-Time ASL Gesture Recognition

A real-time hand gesture recognition system using MediaPipe hand landmarks and machine learning.

### 🖱️ Virtual Mouse

A computer-vision-based virtual mouse controlled using hand landmarks and gestures.

### 😴 Drowsiness Detection

A real-time eye-based system for detecting potential drowsiness using facial landmarks.

### 🎮 Hand Tracking Game

A real-time interactive game controlled through hand tracking.

### 🛣️ Lane Detection

Lane detection using classical Computer Vision techniques.

### 📷 Camera Calibration

Camera calibration and geometric measurements using OpenCV.

### 🔤 OCR Applications

Experiments with Tesseract, Keras-OCR, and PaddleOCR for text detection and recognition.

## 📁 Repository Structure

```text
Computer-Vision-Course/
│
├── README.md
├── .gitignore
├── requirements-dlib.txt
├── requirements-paddleocr.txt
│
├── 01-OpenCV/
├── 02-OCR/
├── 03-Object-Detection/
├── 04-Tracking/
├── 05-MediaPipe/
├── 06-Classification/
├── 07-Camera-Geometry/
│
└── Projects/
    ├── ASL-Gesture-Recognition/
    ├── Virtual-Mouse/
    ├── Drowsiness-Detection/
    ├── Lane-Detection/
    └── Hand-Tracking-Game/
```

The repository structure may evolve as projects are cleaned, reorganized, and converted from course exercises into more complete applications.

## 🧪 Development Environment

The projects were developed using Python environments dedicated to different Computer Vision requirements.

### General Computer Vision Environment

```text
Python 3.11
```

Dependencies:

```text
requirements-dlib.txt
```

### OCR Environment

```text
Python 3.11
```

Dependencies:

```text
requirements-paddleocr.txt
```

The exact package versions are provided in the requirements files to improve reproducibility.

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Computer-Vision-Course.git
cd Computer-Vision-Course
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\activate
```

Install the required packages:

```bash
pip install -r requirements-dlib.txt
```

For projects requiring the OCR environment:

```bash
pip install -r requirements-paddleocr.txt
```

## 📌 Important Note About Datasets and Large Files

Large datasets, videos, audio files, virtual environments, generated files, and other unnecessary local resources are intentionally excluded from the repository.

The repository focuses primarily on:

* Source code
* Jupyter notebooks
* Project documentation
* Configuration files
* Selected lightweight assets

Large datasets and model files may be provided separately when necessary and appropriate.

## 📈 Learning Progression

The work in this repository progresses from fundamental Computer Vision concepts toward more advanced real-time applications:

```text
Python
   ↓
NumPy
   ↓
OpenCV
   ↓
Image Processing
   ↓
Feature Detection
   ↓
Object Detection
   ↓
Object Tracking
   ↓
OCR
   ↓
Machine Learning
   ↓
Deep Learning
   ↓
MediaPipe
   ↓
Real-Time Computer Vision Applications
```

## 🎓 Course Work vs. Independent Projects

Some notebooks in this repository were developed as part of structured Computer Vision coursework and experimentation.

Selected projects are further organized separately to demonstrate practical application development beyond individual course exercises.

## 🔬 Future Improvements

Planned improvements include:

* Converting important notebooks into standalone Python applications
* Improving project documentation
* Adding demonstrations and screenshots
* Adding quantitative evaluation metrics
* Improving code organization
* Adding reusable Computer Vision modules
* Developing more real-time applications
* Exploring modern object detection and tracking architectures
* Integrating Computer Vision with embedded and real-world systems

## 👨‍💻 Author

**Mohamed Saleh**

Engineering Student | Computer Vision & AI

Interested in:

* Computer Vision
* Artificial Intelligence
* Robotics
* Embedded Systems
* Real-Time Vision Systems
* AI Engineering

---

⭐ This repository documents my practical Computer Vision learning journey and the projects I have developed while building my skills in real-time vision and AI.

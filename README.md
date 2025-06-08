# ObjDetect 🔍

A fast and easy-to-use Python object detection script using OpenCV's DNN module and the SSD MobileNet model pretrained on the COCO dataset. 🤖

![ObjDetect Demo](https://github.com/KrishBharadwaj5678/ObjDetect/raw/main/ObjDetectDemo.png)  

---

## Features ✨

| Feature                                                                 |
|-------------------------------------------------------------------------|
| 🏷️ Detects 80 common object classes (COCO dataset) in images           |
| ⚡ Lightweight SSD MobileNet architecture for real-time performance     |
| 🐍 Simple Python script using OpenCV, no heavy frameworks required      |
| 🎥 Easily extendable to video and real-time camera input                |
| 🧠 Uses pretrained deep learning model                                  |
| 🖼️ Supports high-resolution image inputs                               |
| 🧩 Modular code structure for easy customization                       |

---

## Tech Stack 🧰

| Technology       | Description                                                  |
|------------------|--------------------------------------------------------------|
| 🐍 Python        | Core programming language for scripting and logic            |
| 🧠 OpenCV (cv2)  | Used for image processing and loading the DNN model          |
| 🤖 SSD MobileNet | Lightweight object detection model pretrained on COCO        |
| 🗂️ COCO Dataset  | Dataset with 80 common object classes used for detection     |

---


## Installation 🛠️

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/ObjDetect.git
   cd ObjDetect
   ```

2. Install dependencies:

   ```bash
   pip install opencv-python
   ```

3. Download required model files and class names:

   - `frozen_inference_graph.pb` (SSD MobileNet weights) 📦  
   - `ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt` (config file) ⚙️  
   - `coco.names` (class labels) 🏷️  

   *(You can find these files in the TensorFlow detection model zoo or included in this repo if you want.)*

---

## Usage ▶️

1. Place your input image in the repo directory (e.g., `photo.jpg`).  
2. Run the detection script:

   ```bash
   python detect.py
   ```

3. The output window will show detected objects with bounding boxes and labels. 🖼️✔️

---

## How It Works ⚙️

- Loads the COCO class labels from `coco.names`. 🏷️  
- Loads the SSD MobileNet model with OpenCV’s DNN module. 🤖  
- Preprocesses the image and performs detection. 🔍  
- Draws bounding boxes and class labels on detected objects. 📦


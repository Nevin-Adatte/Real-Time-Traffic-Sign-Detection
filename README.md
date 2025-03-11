# Real-Time Traffic Sign Detection

## Overview
This project focuses on real-time traffic sign detection and classification using **YOLOv5**. The system identifies traffic signs within a video feed or image, enclosing them in bounding boxes with labels. It achieves high accuracy and operates at real-time speeds.

---

## 🔧 Installation & Setup

1. **Extract Files**  
   - Unzip the repository and navigate to the project directory.
   - Locate `Models.zip` inside the directory and extract it.

2. **Install Dependencies**  
   - Using pip:  
     ```bash
     pip install -r requirements.txt
     ```
   - Using Anaconda:  
     ```bash
     conda install --file requirements.txt
     ```

3. **Run Detection**  
   - For an image or video file:  
     ```bash
     python detect.py --source path/to/your/file
     ```
   - Example for an image named `test.jpg`:  
     ```bash
     python detect.py --source Test/test.jpg
     ```
   - For live camera feed:  
     ```bash
     python detect.py --source 0
     ```

4. **Results**  
   - Detection results will be saved in the `Results` folder.

---

## 📂 Project Structure

**Real-Time-Traffic-Sign-Detection-main**\
├───Codes\
│ ├───models\
│ │ ├───hub\
│ │ └───__pycache__\
│ └───utils\
│ ├───google_app_engine\
│ └───__pycache__\
├───Model\
│ └───weights\
├───Results\
└───Test

---

## 📊 Performance
- Trained on **3000 images** for **61 traffic sign classes**.
- Achieved **91.75% mAP@0.5**.
- Real-time speed: **28-45 FPS** on a **GeForce MX250**.

---


🚀 **Ready to Detect Traffic Signs in Real Time!**



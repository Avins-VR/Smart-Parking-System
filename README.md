# 🅿️ Smart Parking Management System using OpenCV

This project is a **computer vision–based smart parking management system** designed to help drivers quickly identify available parking spaces.  
It uses **OpenCV**, **mask images**, and **color images/videos** to detect parking occupancy in **real time**, making parking faster, more efficient, and hassle-free.

---

## 🚀 Project Objective

- Assist drivers in finding free parking spaces quickly  
- Reduce time spent searching for parking  
- Improve parking efficiency using computer vision  
- Enable real-time parking occupancy detection  

---

## 🧠 System Overview

The system processes live video or recorded footage of a parking area and determines whether each parking spot is **occupied or empty** using **mask-based image analysis**.

---

## 🖼️ Detection Methodology

- **Mask Images** are used to define individual parking slots  
- **Color Images / Video Frames** are analyzed in real time  
- Pixel intensity and thresholding techniques determine occupancy  

---

## 🎨 Visual Output

- 🟩 **Green Box** → Occupied Parking Spot  
- 🟥 **Red Box** → Empty Parking Spot  

This visual feedback allows users to instantly identify available spaces.

---

## 🛠️ Technologies & Libraries Used

### 🔧 Programming Language
- Python

### 📚 Libraries & Tools
- OpenCV
- NumPy
- Matplotlib
- cvzone (optional)

---

## ⚙️ Workflow

1. Load parking lot video or camera feed  
2. Apply predefined mask images to mark parking slots  
3. Extract each parking region  
4. Analyze pixel density / threshold values  
5. Classify slot as **occupied** or **empty**  
6. Display bounding boxes with color indicators  

---

## ▶️ How to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/smart-parking-opencv.git

# Navigate to the project directory
cd smart-parking-opencv

# Install required libraries
pip install -r requirements.txt

# Run the parking detection system
python main.py

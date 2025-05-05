

## 💤 Drowsiness and Yawn Detection with Integrated Voice Alert System

### 🚀 Overview

This project is an AI-powered **drowsiness and yawn detection system** designed to enhance safety by monitoring driver alertness. It uses **OpenCV**, **Dlib**, and **machine learning** techniques to detect eye closure and yawning in real-time. If signs of fatigue are detected, a **voice alert system** is triggered to wake the driver.

---

### 🎯 Features

* 👁️ Real-time **eye and mouth detection**
* 💤 Drowsiness detection using **Eye Aspect Ratio (EAR)**
* 😮 Yawn detection using **Mouth Aspect Ratio (MAR)**
* 🔊 **Voice alerts** to warn the driver
* 📷 Live webcam feed analysis with visual feedback

---

### 🛠️ Technologies Used

* Python 3.x
* OpenCV
* Dlib
* Imutils
* Scipy
* Pygame / Pyttsx3 (for voice alerts)

---

### 📁 Project Structure

``` bash
Drowsiness-Yawn-Detection/
│
├── models/
│   └── shape_predictor_68_face_landmarks.dat     # Dlib facial landmarks model
│
├── music.wav                                     # Audio file for voice alert
│
├── detect_drowsiness.py                          # Main Python script
│
├── requirements.txt                              # Python dependencies
│
├── README.md                                     # Project documentation
│
```


---

### 🔧 Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/Drowsiness-Yawn-Detection.git
cd Drowsiness-Yawn-Detection
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Download the facial landmark model**
   Download `shape_predictor_68_face_landmarks.dat` from [Dlib model link](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2), extract it, and place it in the project folder.

---

### ▶️ Usage

```bash
python detect_drowsiness.py
```

* Ensure your webcam is connected.
* Stay within camera frame for proper face detection.
* The system will issue a **voice alert** if drowsiness or yawning is detected.

---



### 📚 References

* Tereza Soukupová and Jan Čech – Real-Time Eye Aspect Ratio Calculation
* Dlib 68 Facial Landmark Detection
* OpenCV Documentation

---

### 🤝 Contributing

Feel free to fork this project and submit pull requests. Contributions and improvements are welcome!

---



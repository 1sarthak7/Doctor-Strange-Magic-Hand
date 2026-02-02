#  Doctor Strange Magic Hand Effect using Python

A real-time **computer vision project** that uses a webcam to detect hands and render **Doctor Strange–style magical effects** on the user’s palms. Built using **OpenCV** and **MediaPipe**, this project demonstrates gesture-based AR overlays with smooth tracking and animated visual effects.

---

##  Features

* Real-time **hand detection & tracking** using MediaPipe
* **Magic circle visual effects** rendered on both hands
* Supports **clockwise & counter-clockwise animated overlays**
* Accurate palm positioning using hand landmarks
* Live webcam feed with alpha-blended PNG effects
* Lightweight & fast (runs on CPU)

---

##  How It Works

1. Webcam captures live video frames
2. MediaPipe detects hand landmarks (21 key points per hand)
3. Palm and finger landmark positions are calculated
4. Magic circle PNGs are rotated frame-by-frame
5. Effects are alpha-blended onto the detected hand positions
6. Result is displayed in real time

---

##  Tech Stack

* **Python 3**
* **OpenCV** – video capture & rendering
* **MediaPipe** – hand landmark detection
* **NumPy** – image processing

---

##  Project Structure

```
├── main.py
├── magic_circles/
│   ├── magic_circle_ccw.png
│   ├── magic_circle_cw.png
└── README.md
```

---

##  Installation & Setup

### 1 Clone the Repository

```bash
git clone https://github.com/1sarthak7/Doctor-Strange-Magic-Hand.git
cd Doctor-Strange-Magic-Hand
```

### 2 Install Dependencies

```bash
pip install opencv-python mediapipe numpy
```

### 3 Run the Project

```bash
python main.py
```


---

##  Controls & Gestures

* Show your **palm to the camera** to activate the magic circle
* Rotate or move your hand to see the effect follow naturally
* Works with **one or both hands**

---

##  Author

**Sarthak Bhopale**
Aspiring Engineer | Computer Vision & Creative Dev

---
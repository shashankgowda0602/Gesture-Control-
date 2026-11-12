# Gesture Control 🎮🖐️

Control your computer with hand gestures – AI-powered touchless interaction using Python and Computer Vision.

This project uses:

* OpenCV
* MediaPipe
* PyAutoGUI

to detect hand gestures and convert them into touchless interaction like:

* Next Slide
* Previous Slide
* Start Presentation
* Exit Presentation

---

# 🚀 Features

✅ Control Google Slides using gestures  
✅ Real-time hand tracking using AI  
✅ Works directly from laptop webcam  
✅ No additional hardware required  
✅ Beginner-friendly AI + Computer Vision project

---

# 🧠 Gesture Controls for presentation

| Gesture          | Action          |
| ---------------- | --------------- |
| ✋ Open Palm      | Next Slide      |
| 🤟 Three Fingers | Previous Slide  |
| ✌️ Two Fingers   | Start Slideshow |
| ✊ Fist           | Exit Slideshow  |

---

# 🛠️ Technologies Used

* Python
* OpenCV
* MediaPipe
* PyAutoGUI

---

# 📦 Installation

## Prerequisites

Make sure you have Python 3 installed on your system.

- On Windows, use `py` in the commands below.
- On macOS and Linux, use `python3`.

Check Python is installed:

**Windows (PowerShell):**

```powershell
py --version
```

**macOS / Linux:**

```bash
python3 --version
```

## Step 1 — Download the code

Clone the repository or download the project ZIP file to your computer.

```bash
git clone https://github.com/shashankgowda0602/Gesture-Control-.git
cd Gesture-Control-
```

If you downloaded the ZIP file instead, extract it and open the project folder.

## Step 2 — Install Dependencies

Create and activate a virtual environment (recommended):

**Windows (PowerShell):**

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
```

**macOS / Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Install the required Python packages:

**Windows:**

```powershell
py -m pip install --upgrade pip
py -m pip install -r requirements.txt
```

**macOS / Linux:**

```bash
python3 -m pip install --upgrade pip
python3 -m pip install -r requirements.txt
```

## Step 3 — Download Hand Landmarker Model

This project needs the MediaPipe hand model file before running.

Run the setup script from the project folder:

**Windows:**

```powershell
py setup_models.py
```

**macOS / Linux:**

```bash
python3 setup_models.py
```

This downloads the model into the `models/` folder as `hand_landmarker.task`.

## ▶️ Run the App

With the virtual environment still activated, start the app:

**Windows:**

```powershell
py main.py
```

**macOS / Linux:**

```bash
python3 main.py
```

Open Google Slides and begin your presentation. Then show the gestures in front of your webcam to control the slides.

To stop the app, press `Ctrl+C` in the terminal.

---

# 💻 macOS Permission Setup

For keyboard control to work on macOS, go to:

**System Settings → Privacy & Security**

Enable permissions for:

* Accessibility
* Input Monitoring

Allow access for the application you use to run the project, such as Terminal, VS Code, or PyCharm. Without these permissions, the app cannot control Google Slides.

---

# 🎯 How to Use

1. Open Google Slides in Chrome.
2. Start slideshow mode.
3. Run the Python application.
4. Show gestures in front of the webcam.
5. Control slides hands-free.

---

# 📂 Project Structure

```text
Gesture-Control-/
├── .gitignore
├── main.py
├── README.md
├── requirements.txt
├── setup_models.py
└── models/
    └── hand_landmarker.task
```

---

# 📜 requirements.txt

```txt
mediapipe==0.10.35
opencv-python>=4.8.0
pyautogui>=0.9.54
```

---

# 🧩 How It Works

The application:

1. Captures webcam feed using OpenCV.
2. Detects hand landmarks using MediaPipe.
3. Identifies finger positions.
4. Maps gestures to keyboard shortcuts.
5. Uses PyAutoGUI to control Google Slides.

---

# 🔮 Future Improvements

* Swipe gesture recognition
* Gesture-based laser pointer
* Volume control
* Zoom gestures
* AI-powered custom gesture training
* Multi-hand support

---

# 🎓 Learning Outcomes

This project helps students understand:

* Computer Vision
* AI-based gesture recognition
* Human Computer Interaction (HCI)
* Real-time webcam processing
* Automation using Python

---

# 📸 Demo Idea

Use this project during:

* AI Workshops
* Hackathons
* College Tech Fests
* Computer Vision Sessions
* Smart Classroom Demonstrations

---

# ⚠️ Notes

* Ensure good lighting conditions.
* Keep your hand visible to the webcam.
* Avoid cluttered backgrounds for better detection.
* Works best at moderate camera distance.

---

# Live MediaPipe 
![MediaPipe Hand Tracking Demo](https://google-ai-edge.github.io/mediapipe-samples-web/#/vision/hand_landmarker)
![Google AI Media Pipe] (https://ai.google.dev/edge/mediapipe/solutions/guide)

---

# 👨‍💻 Built With AI + Computer Vision

A futuristic interaction system powered by hand tracking and real-time gesture recognition.

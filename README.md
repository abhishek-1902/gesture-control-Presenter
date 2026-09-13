Gesture Control Presenter 🎮🖐️

Control your Google Slides presentations using hand gestures through your laptop camera using Computer Vision and AI.

This project uses:

* OpenCV
* MediaPipe
* PyAutoGUI

to detect hand gestures and convert them into presentation controls like:

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

# 🧠 Gesture Controls

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

— Install Dependencies

python -m pip install --break-system-packages -r requirements.txt
```

— Download Hand Landmarker Model

python setup_models.py
```

---

# ▶️ Run the App

```bash
python main.py
```


# Close the application

Press Ctrl+C in terminal to close the application



# How to Use

1. Open Google Slides in Chrome
2. Start slideshow mode
3. Run the Python application
4. Show gestures in front of webcam
5. Control slides hands-free


# 📜 requirements.txt

mediapipe==0.10.35
opencv-python>=4.8.0
pyautogui>=0.9.54
```


# 🧩 How It Works

The application:

1. Captures webcam feed using OpenCV
2. Detects hand landmarks using MediaPipe
3. Identifies finger positions
4. Maps gestures to keyboard shortcuts
5. Uses PyAutoGUI to control Google Slides

---
 🎓 Learning Outcomes

* Computer Vision
* AI-based gesture recognition
* Human Computer Interaction (HCI)
* Real-time webcam processing
* Automation using Python

---
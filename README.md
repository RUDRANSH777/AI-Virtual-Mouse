# 🖱️ AI Virtual Mouse

Ever wondered if you could control your computer without touching a mouse? This project makes that possible by using your webcam and hand gestures. With the help of Computer Vision and AI, the system tracks your hand movements in real time and translates them into mouse actions such as moving the cursor and clicking.

## 🚀 What This Project Does

AI Virtual Mouse allows you to interact with your computer using simple hand gestures. Instead of using a physical mouse, you can move your hand in front of the camera to control the cursor and perform clicks naturally.

This project was built to explore the practical applications of Artificial Intelligence, Computer Vision, and Human-Computer Interaction.

## ✨ Features

* Move the cursor using your index finger
* Perform left-click actions using hand gestures
* Support for double-click gestures
* Real-time hand tracking through a webcam
* Smooth and responsive cursor movement
* Hands-free and touchless computer control

## 🛠️ Technologies Used

* **Python** – Core programming language
* **OpenCV** – Webcam access and image processing
* **MediaPipe** – Real-time hand landmark detection
* **PyAutoGUI** – Mouse control automation

## 📂 How It Works

1. The webcam captures live video frames.
2. MediaPipe detects and tracks hand landmarks.
3. Finger positions are analyzed to identify gestures.
4. The detected gestures are converted into mouse actions.
5. PyAutoGUI executes the corresponding cursor movement or click event.

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/AI-Virtual-Mouse.git
cd AI-Virtual-Mouse
```

Install the required dependencies:

```bash
pip install opencv-python mediapipe pyautogui
```

Run the application:

```bash
python virtual_mouse.py
```

## 🎮 Gesture Controls

| Gesture              | Action       |
| -------------------- | ------------ |
| Index Finger         | Move Cursor  |
| Thumb + Index Finger | Left Click   |
| Two-Finger Gesture   | Double Click |

## 🔮 Future Improvements

* Gesture-based volume control
* Brightness adjustment using hand movements
* Drag-and-drop functionality
* Scrolling gestures
* Multi-hand support
* Custom gesture mapping

## 📚 What I Learned

While building this project, I gained hands-on experience with:

* Computer Vision fundamentals
* Real-time hand tracking
* Human-Computer Interaction concepts
* AI-powered gesture recognition
* Integrating multiple Python libraries into a complete application

If you like this project, feel free to ⭐ star the repository and share your feedback!

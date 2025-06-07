# AI-Virtual-Machine
🖱️ AI Virtual Mouse using Hand Gestures
Control your computer using just your hands! This Python-based AI Virtual Mouse uses computer vision and hand tracking to simulate mouse movements and actions like clicks, scrolls, and system volume/brightness control.

🚀 Features
Hand gesture detection with MediaPipe

Mouse movement with fingertip tracking

Left/right click, double-click, and drag using gestures

Scroll up/down and horizontally using two-finger pinch

Volume and brightness control using gestures

Multi-hand support (left & right hand gestures)

# 📽️ Demo
🎥 [Add your demo video link here, e.g. YouTube or Loom]

# 🛠️ Technologies Used
Python

OpenCV

MediaPipe

PyAutoGUI

Pycaw (Volume control)

screen_brightness_control (Brightness control)

Google Protobuf

# 📦 Installation
bash
Copy
Edit

# Clone the repository
git clone https://github.com/your-username/ai-virtual-mouse.git
cd ai-virtual-mouse

# Install required packages
pip install -r requirements.txt


# 🧠 How It Works
Uses MediaPipe Hands to detect and track hand landmarks in real-time.

Classifies gestures like pinch, V-sign, and fist to control mouse events.


# Gesture mappings:

✌️ V Sign → Move Mouse

✊ Fist → Click & Hold

👉 Index → Right Click

✌️ (Close) → Double Click

🤏 (Minor Pinch) → Scroll

🤏 (Major Pinch) → Volume / Brightness Control

# 📁 Project Structure
bash
Copy
Edit
├── ai_virtual_mouse.py     # Main script
├── README.md
└── requirements.txt

# 🧪 How to Run
bash
Copy
Edit
python ai_virtual_mouse.py
Ensure your webcam is connected.

Use hand gestures in front of the camera to control your system.

# 📸 Screenshots
[Add a few screenshots showing the gesture and its action]

# 💡 Future Improvements
Add GUI interface for calibration

Gesture customization

Add voice commands for hybrid control

# 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.



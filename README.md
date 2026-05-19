# Hill-Climb-Racing-game-using-Hand-Gestures
A real-time gesture-controlled version of Hill Climb Racing developed using Python, OpenCV, MediaPipe, and Pynput. The system detects hand gestures through a webcam and converts them into game controls like acceleration and braking, enabling touchless gameplay using computer vision.
Hill Climb Racing Game Using Hand Gestures

A real-time gesture-controlled version of the Hill Climb Racing game built using Python, OpenCV, MediaPipe, and Pynput. This project replaces traditional keyboard controls with hand gestures detected through a webcam, creating an interactive and touchless gaming experience using computer vision.

🚀 Features 
🎮 Control the game using hand gestures
📷 Real-time hand tracking using webcam
✋ Gesture recognition with MediaPipe
⌨️ Keyboard event simulation using Pynput
⚡ Smooth and responsive gameplay
🧠 Demonstrates Human-Computer Interaction (HCI) concepts
🛠️ Technologies Used
Python
OpenCV
MediaPipe
Pynput
📌 Project Workflow
Capture live video using webcam through OpenCV.
Detect hand landmarks using MediaPipe Hands.
Identify whether fingers are open or closed.
Recognize gestures based on finger positions.
Convert gestures into keyboard actions using Pynput.
Control the Hill Climb Racing game in real time.
✋ Gesture Controls
Gesture	Action
✊ Fist (All fingers closed)	Brake
🖐️ Open Palm (All fingers open)	Accelerate (Gas)
🧠 How It Works
MediaPipe detects 21 hand landmarks.
Finger positions are analyzed using landmark coordinates.
The system counts the number of open fingers:
0 fingers open → Brake
5 fingers open → Accelerate
Pynput simulates keyboard arrow key presses based on the detected gesture.
📂 Project Structure
Hill-Climb-Racing-Hand-Gesture/
│
├── main.py
├── README.md
└── requirements.txt
▶️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/Hill-Climb-Racing-Hand-Gesture.git
cd Hill-Climb-Racing-Hand-Gesture
2️⃣ Install Dependencies
pip install opencv-python mediapipe pynput
3️⃣ Run the Project
python main.py
💡 Future Enhancements
Add more gestures (Jump, Tilt, Reverse)
Improve gesture smoothing and stability
Multi-hand support

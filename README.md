✋ Hand Gesture Control using Ultrasonic Sensors
This project allows you to control computer functions using hand gestures by reading distance values from two ultrasonic sensors. The system combines Arduino for sensor input and Python for interpreting gestures to perform actions on a computer.

🎯 Project Overview
Uses 2 Ultrasonic Sensors (HC-SR04) to detect hand positions/distance.

Arduino reads the distance data and sends it to the computer via serial.

A Python script processes this data to trigger actions like scrolling, volume control, etc.

Works like a basic gesture recognition system for real-world use.

🛠️ Tech Stack
Component	Description
Hardware	Arduino Uno, 2x HC-SR04 Sensors
Arduino Code	Reads distances and sends over serial
Python Code	Reads serial input and maps distances to system actions
OS Compatibility	Windows/Linux (via Python + pySerial/pyautogui)

🔧 How It Works
Place two ultrasonic sensors side by side.

Move your hands in front of the sensors.

Arduino sends real-time distance values to the Python program.

Python script converts gestures into actions like:

Volume up/down

Scroll up/down

 click

📁 Files Included
aurduinocode.cpp – Arduino sketch for reading ultrasonic sensors

pythoncode.py – Python script to read serial data and trigger system actions

🚀 Setup Instructions
Upload Arduino Code:

Open hand_gesture.ino in Arduino IDE.

Connect Arduino via USB and upload the code.

Run Python Script:

Install dependencies:

pip install pyserial pyautogui
Run the script:

python pythoncode.py
Start Controlling!

Move your hands at different distances.

Trigger actions based on proximity.

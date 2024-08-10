# Automated-Media-Player-using-Hand-Gestures
This project is an Automated Media Player that allows users to control media playback using hand gestures. It leverages computer vision and machine learning technologies to provide an intuitive and natural way of interacting with media devices, making hands-free operation possible.

**Features:**
1. Hand Landmark Detection: Detects 21 hand landmarks, including fingertips, knuckles, and the wrist.
2. Real-time Gesture Recognition: Processes hand gestures in real-time to perform media control actions.
3. Media Control: Supports gestures for playing/pausing, navigating tracks, adjusting volume, and more.
4. Hands-Free Operation: Allows interaction without touching the device, ideal for various scenarios like cooking, exercising, or accessibility needs.
5. Customizable Gestures: Easily extendable to include additional gestures for more controls.

![Landmark Image](./landmark.png)

**Getting Started:** <br/> 
Follow these steps to run the Automated Media Player on your device.

1. Prerequisites:
Python 3.x
Pip (Python package installer)

2. Installation:
Clone the Repository:<br/> 
 ```
git clone https://github.com/yourusername/automated-media-player.git
cd automated-media-player
 ``` 

3. Install Dependencies:
```
pip install opencv-python mediapipe pyautogui
```

5. Navigate to the Project Directory:
```
cd automated-media-player
```

7. Run the Python Script:
```
python media_player.py
```

8. Usage:<br/>   
Ensure your webcam is connected and working.<br/> 
The script will open a window showing the video feed from your webcam.<br/> 
Use the following gestures to control media playback:<br/> 
One Finger Up: Skip to the next track.<br/> 
Two Fingers Up: Go to the previous track.<br/> 
Three Fingers Up: Increase volume.<br/> 
Four Fingers Up: Decrease volume.<br/> 
Five Fingers Up: Play/Pause.

*Contributing* 🤝<br/> 
Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or bug fixes.

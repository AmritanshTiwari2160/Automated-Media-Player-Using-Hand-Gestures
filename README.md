# Automated-Media-Player-using-Hand-Gestures
This project is an Automated Media Player that allows users to control media playback using hand gestures. It leverages computer vision and machine learning technologies to provide an intuitive and natural way of interacting with media devices, making hands-free operation possible.

## Features:
1. Hand Landmark Detection: Detects 21 hand landmarks, including fingertips, knuckles, and the wrist.
2. Real-time Gesture Recognition: Processes hand gestures in real-time to perform media control actions.
3. Media Control: Supports gestures for playing/pausing, navigating tracks, adjusting volume, and more.
4. Hands-Free Operation: Allows interaction without touching the device, ideal for various scenarios like cooking, exercising, or accessibility needs.
5. Customizable Gestures: Easily extendable to include additional gestures for more controls.

## Diagrammatic Representation of Hand Landmarks

![Landmark Image](./Hand_Landmarks.png)

### Hand Joints and Landmarks

1. **WRIST**: Wrist
2. **THUMB_CMC**: Thumb Carpometacarpal Joint
3. **THUMB_MCP**: Thumb Metacarpophalangeal Joint
4. **THUMB_IP**: Thumb Interphalangeal Joint
5. **THUMB_TIP**: Thumb Tip
6. **INDEX_FINGER_MCP**: Index Finger Metacarpophalangeal Joint
7. **INDEX_FINGER_PIP**: Index Finger Proximal Interphalangeal Joint
8. **INDEX_FINGER_DIP**: Index Finger Distal Interphalangeal Joint
9. **INDEX_FINGER_TIP**: Index Finger Tip
10. **MIDDLE_FINGER_MCP**: Middle Finger Metacarpophalangeal Joint
11. **MIDDLE_FINGER_PIP**: Middle Finger Proximal Interphalangeal Joint
12. **MIDDLE_FINGER_DIP**: Middle Finger Distal Interphalangeal Joint
13. **MIDDLE_FINGER_TIP**: Middle Finger Tip
14. **RING_FINGER_MCP**: Ring Finger Metacarpophalangeal Joint
15. **RING_FINGER_PIP**: Ring Finger Proximal Interphalangeal Joint
16. **RING_FINGER_DIP**: Ring Finger Distal Interphalangeal Joint
17. **RING_FINGER_TIP**: Ring Finger Tip
18. **PINKY_MCP**: Pinky Metacarpophalangeal Joint
19. **PINKY_PIP**: Pinky Proximal Interphalangeal Joint
20. **PINKY_DIP**: Pinky Distal Interphalangeal Joint
21. **PINKY_TIP**: Pinky Tip

## Getting Started: 
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

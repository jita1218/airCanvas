# AirCanvas

## Introduction
AirCanvas is a hand-gesture-based drawing application built using Python, OpenCV, and Mediapipe. With this project, you can draw in the air using your fingers, creating an interactive painting experience without the need for a physical stylus or mouse. The webcam detects your hand, tracks your fingertip, and translates those movements into real-time drawing on a digital canvas.

## Features
- Draw with finger gestures using a webcam
- Multiple color options: Blue, Green, Red, Yellow
- Clear the canvas with a simple gesture
- Interactive UI with color selection buttons
- Real-time hand and finger tracking powered by Mediapipe

## Demo


## How It Works
- The webcam detects hand movements and tracks the tip of your index finger.
- When the thumb is brought close to the index finger, the system interprets it as the action to start drawing.
- The user can select different colors by hovering over color buttons at the top of the screen.
- You can also clear the canvas by selecting the "CLEAR" button.

## How to Use
- **Start Drawing:** Position your hand so the webcam can detect it. Bring your thumb close to your index finger to start drawing.
- **Change Colors:** Hover your finger over the desired color button (Blue, Green, Red, or Yellow) at the top of the canvas to change the drawing color.
- **Clear Canvas:** Hover over the "CLEAR" button to erase the entire canvas.
- **Quit:** Press `q` to exit the application.

## Acknowledgments
I would like to thank Aryan (https://github.com/infoaryan) for their excellent tutorial on creating an AirCanvas. This project was inspired by his [YouTube video](https://youtu.be/T7sjrWc4QEc?si=CXAkRszBN9nETBMv) that guided me through the hand-tracking and drawing techniques using Python, OpenCV, and Mediapipe.

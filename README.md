# Air Canvas

Air Canvas is an interactive drawing application that allows users to draw in the air using hand gestures. Leveraging the power of OpenCV and MediaPipe, this project tracks hand movements to enable seamless drawing on a digital canvas.

## Features
- **Air Drawing:** Use your index finger to draw on the canvas with different colors.
- **Color Selection:** Easily switch between blue, green, red, and yellow colors using intuitive gestures.
- **Clear Canvas:** Clear the entire canvas with a simple gesture.
- **Real-Time Hand Tracking:** Utilizes MediaPipe for accurate and efficient hand tracking.

## Installation
### Prerequisites
- Python 3.6 or higher
- OpenCV
- NumPy
- MediaPipe

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ParthChande/AirCanvas.git
   cd AirCanvas
   ```
## Controls
- Drawing: Move your index finger to draw on the canvas.
- Color Selection:
-  Move your finger over the desired color button at the top of the screen and pinch with your -  thumb to select.
- Available colors: BLUE, GREEN, RED, YELLOW.
Clear Canvas: Move your finger over the "CLEAR" button at the top left of the screen and pinch with your thumb to clear the canvas.

# How It Works
1. Hand Detection: Uses MediaPipe to detect and track hand landmarks in real-time.
2. Gesture Recognition: Identifies the position of the index finger and thumb to interpret gestures.
3. Drawing Logic: Draws lines on the canvas based on the movement of the index finger, changing colors or clearing the canvas based on user gestures.

# Code Structure
- air_canvas.py: The main application file that contains all the logic for hand tracking and drawing.

# Output
![cam](https://github.com/user-attachments/assets/66f976c9-6c14-40e0-8baf-331284ceca73)


# Dependencies
opencv-python-headless: OpenCV library for image processing.
numpy: Library for numerical operations.
mediapipe: MediaPipe library for hand tracking.


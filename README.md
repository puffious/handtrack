# Hand Tracking Mouse Control

This project allows you to control your computer mouse using hand gestures captured through your webcam.

## Setup Instructions

### 1. Create a Python Virtual Environment

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 2. Install Required Dependencies

```bash
# Install all required packages
pip install -r requirements.txt
```

### 3. Run the Application

```bash
python main.py
```

## How to Use

Position your hand in front of the webcam and use the following gestures:

1. **Move Cursor**: Raise your index finger and keep other fingers down.
   - The cursor will follow the movement of your index finger.

2. **Click**: Raise both index and middle fingers and bring them close together.
   - When the distance between the fingers is less than 40 pixels, a click is performed.

3. **Drag and Drop**:
   - **Start Drag (Mouse Down)**: Raise thumb and index finger and bring them close together.
   - **End Drag (Mouse Up)**: Raise middle and ring fingers while keeping index finger down.

4. **Exit Program**: Press any key while the webcam window is in focus.

## Notes

- Make sure your hand is within the purple boundary box displayed on the screen for optimal tracking.
- The frame rate (FPS) is displayed in the top-left corner of the window.
- For best results, use in a well-lit environment with a clear background.
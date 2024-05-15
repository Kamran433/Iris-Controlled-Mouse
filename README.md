# Iris-Controlled-Mouse

**Description:**

This project is an iris-controlled mouse system implemented in Python using computer vision and eye-tracking techniques. The system is designed to track the movement of the user's eyes, specifically the iris, and translate that movement into mouse cursor movements on the screen. This allows users to control the mouse cursor using only their eyes.

**Key Features:**
- Eye Detection and Tracking: The system uses eye detection algorithms to locate the user's eyes in the camera feed and tracks the movement of the iris to determine the direction of gaze.
- Mouse Cursor Control: Based on the detected eye movement, the system controls the mouse cursor on the screen, allowing users to move the cursor by looking at different parts of the screen.
- Click and Drag: The system includes features for simulating mouse clicks and drag-and-drop actions based on predefined eye movement patterns or gestures.
- Calibration: The system includes a calibration process to calibrate the eye tracking system for each user, improving accuracy and responsiveness.
- User Interface: The system provides a user-friendly interface for calibrating the system, adjusting settings, and controlling the mouse cursor using eye movements.
- Customization: The system is customizable, allowing users to adjust sensitivity, speed, and other parameters to suit their preferences and needs.

**Technologies Used:**
- Python: The core programming language used for implementing the system's functionality.
- OpenCV: An open-source computer vision library used for eye detection and tracking.
- Dlib: A C++ toolkit containing machine learning algorithms and tools for creating complex software in C++ to detect facial features.
- PyAutoGUI: A Python module that programmatically controls the mouse and keyboard, used for simulating mouse movements and clicks based on eye movements.
- Tkinter: A GUI toolkit for creating the user interface of the system.

This project showcases how eye-tracking technology can be used to create an innovative and hands-free mouse control system, providing an alternative input method for individuals with physical disabilities or for applications requiring hands-free interaction. The system can be further enhanced with additional features, such as gesture recognition or integration with other assistive technologies.

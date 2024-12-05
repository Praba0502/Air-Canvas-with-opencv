# Air-Canvas-with-opencv


Description:
AirCanvas is an interactive project that enables users to draw on a virtual canvas using hand gestures detected by a webcam. It leverages computer vision to track the movement of a color-marked object and translates these movements into drawings on the screen. Built with Python and OpenCV, this project demonstrates the potential of gesture-based technology for creative and practical applications.

Key Features:
Real-Time Color Detection:
Detects specific colors (like blue, green, red, or yellow) based on adjustable HSV (Hue, Saturation, Value) ranges.
Trackbars allow fine-tuning for precise color detection.

Drawing and Controls:
Enables freehand drawing on a virtual canvas by tracking the movement of a colored object.
Includes a "Clear All" button to reset the canvas for new drawings.
Users can switch between multiple ink colors (blue, green, red, yellow).

Computer Vision Techniques:
HSV Color Space: Used for accurate color-based detection.
Morphological Operations: Erosion, dilation, and contour detection enhance object tracking.
Masking and Filtering: Creates a binary mask for precise object localization.

Applications and Use Cases:
Educational tools for interactive learning and creativity.
Virtual art tools for artists and designers.
Gesture-based interfaces for accessibility and entertainment.

Technologies and Libraries Used:
Python: For scripting and logic implementation.
OpenCV: For image processing and real-time object detection.
Numpy: For numerical operations and data manipulation.

Learning Outcomes:
This project improved my understanding of:
Image processing techniques like contour detection and masking.
Real-time webcam integration with Python.
Practical applications of HSV color space and morphological transformations.
Designing interactive user experiences using computer vision.
AirCanvas is a fun, creative tool showcasing how technology can bridge the gap between physical gestures and digital output.

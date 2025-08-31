## Harry Potter Invisible Cloak Effect (OpenCV Project)
### Project Overview

Ever dreamed of owning Harry Potter’s Invisibility Cloak?
🪄This project recreates that magical effect using Python & OpenCV by leveraging color detection and image masking techniques.

When a person wears a cloak of a specific color (e.g., red/green/blue), the program identifies that color in the video stream and replaces it with the background, making the cloak — and the person wearing it — appear invisible!

### 🎥 How It Works

**1.** Capture the background frame at the start.

**2.** Continuously capture frames from the webcam.

**3.** Convert each frame from BGR → HSV color space for better color detection.

**4.** Apply color thresholding to detect the cloak’s color.

**5.** Use masking and bitwise operations to replace the cloak area with the background.

**6.** Display the final frame where the cloak looks invisible.

### 🛠 Tech Stack

Python
OpenCV (cv2)
NumPy

### ⚡ Features

- Real-time invisibility effect using webcam 🎥
- Adjustable HSV values using trackbars for accurate color detection 🎨
- Works with different cloak colors (just tweak HSV thresholds) 👕
- Fun, beginner-friendly OpenCV project for computer vision learners 🚀

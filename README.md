# Motion Detector
A simple program that captures a video from the computer's camera, detects motion, and sends an email with the image of the object when motion is detected.

# Required Libraries
- cv2
- time
- glob
- emailing (custom module)
- os
- threading

#Usage
The code captures a video from the computer's camera, converts it to grayscale, applies Gaussian Blur to reduce noise, and computes the difference between the current frame and the first frame to detect motion.
When motion is detected, it saves the image of the object, and a custom module emailing is used to send the image through email. A folder named images is created to store the images.

#Features
- Detects motion in a video stream
- Sends an email with the image of the object when motion is detected
- Cleans up the images folder after sending an email

# Interrupt
Press 'q' to interrupt the code and stop the video stream.

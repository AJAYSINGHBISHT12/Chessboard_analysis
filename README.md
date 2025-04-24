Chessboard Square Detector
This project uses OpenCV to detect and label black and white squares on a chessboard image. It processes the image with thresholding and edge detection, finds square contours, and classifies each square based on brightness. The result is a labeled image showing each square's type and the total count of black and white squares.

Features
Detects individual squares on a chessboard

Classifies each as black or white using brightness

Labels each square in the image

Displays final output with total counts

Installation:
command- pip install opencv-python numpy matplotlib

Usage
Replace the image path in the script with your own chessboard image.

Run the script.

View the labeled chessboard and printed square counts.

Example Output:
Total number of Black squares: 32  
Total number of White squares: 32

# Chessboard_analysis
This project detects and labels black and white squares on a chessboard using OpenCV. It processes the image, finds square contours, classifies them based on brightness, and labels each square with its type (black/white) at the center. It also prints the total count of each type.
Chessboard Square Detector
This project uses OpenCV to detect and classify squares on a chessboard image as either black or white based on their brightness. The program processes the image using adaptive thresholding and edge detection, finds square-like contours, calculates the average color for each detected square, and labels them accordingly. It also displays the total count of black and white squares.

Features
Detects individual chessboard squares

Classifies squares as black or white

Labels each square in the image

Displays the final image with classification

Counts total number of each square type

Installation
bash
Copy
Edit
pip install opencv-python numpy matplotlib
Usage
Replace the image path in the script with your chessboard image path.

Run the script.

View the labeled chessboard and square counts.

Output Example
Total number of Black squares: 32

Total number of White squares: 32

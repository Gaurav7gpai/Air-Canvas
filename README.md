# Air-Canvas
The code represents an "Air Canvas" project, which is a basic interactive application that allows users to draw on a virtual canvas using hand gestures captured by a webcam.

The algorithm are break into step by step ,

1. Start reading the frames and convert the captured frames to HSV color space.(Easy for color detection)

2. Prepare the canvas frame and put the respective ink buttons on it.

3. Adjust the values of the mediapipe initialization to detect one hand only.

4. Detect the landmarks by passing the RGB frame to the mediapipe hand detector

5. Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)

6. Finally draw the points stored in array on the frames and canvas. 


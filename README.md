# Virtual-Paint

computer vision Project implemented with OpenCV

I have used computer vision techniques of OpenCV to build this project and the programming language used is python.

Here colour detection and tracking is used to achieve the objective. This project can detect only a few colours but it can be implemented for all the colours via just adding HSV values of the colours.

# Algorithm

1.Start reading the frames and convert the captured frames to HSV colour space.
2.Detect the contours, find the center coordinates of largest contour and keep storing them in the array for successive frames.
3.Finally draw the points stored in array on the frames and canvas.

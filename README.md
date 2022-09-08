# Calibration of Pixel --- Real life measurement of an Object

Many times in image processing and object detection problems, we have to measure sizes of objects from images.

In machine vision, calibration is the process of mapping the pixel coordinate system of the camera sensor to a "world" coordinate system. This mapping defines the relationship between a distance measured in pixels in the camera versus the actual distance in inches or millimeters of the object being imaged.

We can start with these links to understand in a better way-

1. Contour: https://docs.opencv.org/3.4/d4/d73/tutorial_py_contours_begin.html 
2. ImageWarp: https://en.wikipedia.org/wiki/Image_warping#:~:text=Image%20warping%20is%20the%20process,are%20equally%20applicable%20to%20video.
              https://robotacademy.net.au/lesson/image-warping/
              https://pyimagesearch.com/2014/05/05/building-pokedex-python-opencv-perspective-warping-step-5-6/              
3. Dilation & Erosion: https://www.geeksforgeeks.org/difference-between-dilation-and-erosion/ 
4. Canny Edge Detector: https://towardsdatascience.com/canny-edge-detection-step-by-step-in-python-computer-vision-b49c3a2d8123
5. Contour Approximation: https://pyimagesearch.com/2021/10/06/opencv-contour-approximation/

Given all links will give us a brief and depth overview of Contour approximation, Edge Detector, ImageWarping, Image Processing etc.

**Here, we are taking A4 paper as reference and any object which will be situated on the paper, we will get the measurement of those object. 
**But the problem is, It is not generic and we can not say it will work for every image.

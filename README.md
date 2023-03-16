# Visual_guide_for_blind
A sensor camera fitted on a belt conveys the surrounding obstacle information through haptic vibration on a glove.

In this code we use the Kinect sensor and OpenCV library to process depth frames captured by the Kinect sensor.

The code starts by initializing the Kinect sensor and opening the depth stream. It then splits the depth frame into 15 groups, each of size 128x160, and calculates the average pixel value for each group. It then loops through each group and sets the pixels based on their average value.

The processed image is displayed using OpenCV's imshow() function. The while loop continuously captures and processes new depth frames until the program is terminated.

Finally, the code releases the resources and shuts down the Kinect sensor.

This code demonstrates the basic steps involved in processing depth frames from the Kinect sensor using OpenCV.

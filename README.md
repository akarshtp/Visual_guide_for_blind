# Visual_guide_for_blind
A sensor camera fitted on a belt conveys the surrounding obstacle information through haptic vibration on a glove.

In this code we use the Kinect sensor and OpenCV library to process depth frames captured by the Kinect sensor.

The code starts by initializing the Kinect sensor and opening the depth stream. It then splits the depth frame into 15 groups, each of size 128x160, and calculates the average pixel value for each group. It then loops through each group and sets the pixels based on their average value.

The processed image is displayed using OpenCV's imshow() function. The while loop continuously captures and processes new depth frames until the program is terminated.

Finally, the code releases the resources and shuts down the Kinect sensor.

This code demonstrates the basic steps involved in processing depth frames from the Kinect sensor using OpenCV.

# product image
![product](https://github.com/user-attachments/assets/f14eb818-d117-41c0-b0ac-ad3bdce957f0)

# Depth image
![depth_image](https://github.com/user-attachments/assets/99371d80-da0c-4ff6-a37c-2b4dac355644)

# Image matrix

![image_matrix](https://github.com/user-attachments/assets/c4586e7c-7221-4279-9c95-7661aaa59802)


# Haptic feedback

![haptic_feedback](https://github.com/user-attachments/assets/672f83ab-41cf-450b-bc54-abb6ba30bd87)

# Glove connection

![glove_connection](https://github.com/user-attachments/assets/dbabe239-ad31-40ec-9490-3ebe49e03cb1)





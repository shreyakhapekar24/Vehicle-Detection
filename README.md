# Vehicle Detection and Counting System

The Vehicle Detection and Counting System is a computer vision project implemented using the OpenCV library in Python. This system is designed to detect and count vehicles in real-time through video input, making it suitable for various traffic management and monitoring applications. 

What is OpenCV?
OpenCV is a Python open-source library, which is used for computer vision in Artificial intelligence, Machine Learning, face recognition, etc. In OpenCV, the CV is an abbreviation form of a computer vision, which is defined as a field of study that helps computers to understand the content of the digital images such as photographs and videos.
The purpose of computer vision is to understand the content of the images. It extracts the description from the pictures, which may be an object, a text description, and three-dimension model, and so on. For example, cars can be facilitated with computer vision, which will be able to identify and different objects around the road, such as traffic lights, pedestrians, traffic signs, and so on, and acts accordingly.



Project Overview:

The Vehicle Detection and Counting System utilizes computer vision techniques to process video input and identify vehicles within the video frames. It employs background subtraction and contour detection to locate and count vehicles as they pass through a predefined area. Background Subtraction is used to identify moving vehicles (foreground) against a stationary background, while contour detection is employed to create bounding boxes around these vehicles for tracking and counting purposes. The system is capable of counting multiple vehicles simultaneously and provides real-time updates on the count.

Functionalities:

Video Input: The system takes video input, which can be from a live camera feed or a pre-recorded video file.
Vehicle Detection: It employs the MOG (Mixture of Gaussians) background subtraction algorithm to detect moving objects, which are potential vehicles. The system distinguishes vehicles from the background by identifying regions with significant pixel intensity changes.
Contour Detection: Once potential vehicles are detected, the system applies contour detection to create bounding boxes around them. These bounding boxes outline the vehicles in the video frames.
Vehicle Counting: The system counts vehicles by tracking their movement across a predefined line within the video frame (defined by count_line_position). When a vehicle crosses this line, it is counted. The system ensures that it counts only valid vehicles based on predefined width and height thresholds.
Visual Feedback: The system provides visual feedback by drawing bounding rectangles around detected vehicles and displaying the vehicle count on the video frame. It also draws a counting line on the frame to visually represent the counting process.
Real-time Updates: The vehicle count is continuously updated in real-time and displayed on the video frame. This count can be used for various traffic management and monitoring purposes.
User Interaction: The system runs continuously until the user presses the Enter key (key code 13), after which it terminates the video feed and closes any open windows.



![Screenshot (287)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/854a0080-cf2d-45c5-ae49-cdc7e6727ff7)



![Screenshot (289)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/fa1f3143-748f-454c-8b5f-5195e141947a)





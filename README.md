# Vehicle Detection and Counting System

The Vehicle Detection and Counting System is a computer vision project implemented using the OpenCV library in Python. This system is designed to detect and count vehicles in real-time through video input, making it suitable for various traffic management and monitoring applications. 


What is OpenCV?

OpenCV is a Python open-source library, which is used for computer vision in Artificial intelligence, Machine Learning, face recognition, etc. In OpenCV, the CV is an abbreviation form of a computer vision, which is defined as a field of study that helps computers to understand the content of the digital images such as photographs and videos.
The purpose of computer vision is to understand the content of the images. It extracts the description from the pictures, which may be an object, a text description, and three-dimension model, and so on. For example, cars can be facilitated with computer vision, which will be able to identify and different objects around the road, such as traffic lights, pedestrians, traffic signs, and so on, and acts accordingly.


Project Overview:

The Vehicle Detection and Counting System utilizes computer vision techniques to process video input and identify vehicles within the video frames. It employs background subtraction and contour detection to locate and count vehicles as they pass through a predefined area. Background Subtraction is used to identify moving vehicles (foreground) against a stationary background, while contour detection is employed to create bounding boxes around these vehicles for tracking and counting purposes. The system is capable of counting multiple vehicles simultaneously and provides real-time updates on the count.


Functionalities:

1. Video Input: The system takes video input, which can be from a live camera feed or a pre-recorded video file.
2. Vehicle Detection: It employs the MOG (Mixture of Gaussians) background subtraction algorithm to detect moving objects, which are potential vehicles. The system distinguishes vehicles from the background by identifying regions with significant pixel intensity changes.
3. Contour Detection: Once potential vehicles are detected, the system applies contour detection to create bounding boxes around them. These bounding boxes outline the vehicles in the video frames.
4. Vehicle Counting: The system counts vehicles by tracking their movement across a predefined line within the video frame (defined by count_line_position). When a vehicle crosses this line, it is counted. The system ensures that it counts only valid vehicles based on predefined width and height thresholds.
5. Visual Feedback: The system provides visual feedback by drawing bounding rectangles around detected vehicles and displaying the vehicle count on the video frame. It also draws a counting line on the frame to visually represent the counting process.
6. Real-time Updates: The vehicle count is continuously updated in real-time and displayed on the video frame. This count can be used for various traffic management and monitoring purposes.
7. User Interaction: The system runs continuously until the user presses the Enter key (key code 13), after which it terminates the video feed and closes any open windows.




![Screenshot (287)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/854a0080-cf2d-45c5-ae49-cdc7e6727ff7)




![Screenshot (289)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/fa1f3143-748f-454c-8b5f-5195e141947a)




Algorithm Used: 

The primary algorithm used in this project is the MOG (Mixture of Gaussians) background subtraction algorithm. 
This algorithm is used for detecting moving objects in video sequences by modeling each background pixel as a mixture of Gaussians. It is commonly employed in video surveillance and motion detection applications.


Applications:

The Vehicle Detection and Counting System has various applications, including:

1. Traffic management and monitoring
2. Toll booth automation
3. Parking lot occupancy monitoring
4. Security surveillance
5. Congestion detection and management




![Screenshot (295)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/2be9202e-e958-492d-ab17-db64b5ae9835)




![Screenshot (296)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/71c48842-f9d4-413c-b0ad-d3953562cc8b)




Website Integration:

In addition to the Vehicle Detection and Counting System project, a dedicated website has been created to provide users with an interactive and informative experience. This website allows users to fully grasp the benefits and real-world applications of the project. Here are the key features and components of the integrated website:

1. Chat Support: The website includes a chat option that allows users to interact with a support representative or chatbot. Users can ask questions, seek assistance, or request additional information about the project.




![Screenshot (291)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/0c636b36-45eb-4e3e-b58a-8ae7a9848dc3)




2. Functionalities Showcase: The website comprehensively explains the functionalities of the system. Users can explore how it detects and counts vehicles, making it suitable for various traffic management and monitoring applications.




![Screenshot (298)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/c5ee53da-9509-4549-a6bd-d6a9b363dee1)




![Screenshot (309)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/3c43eda2-2549-4875-820d-c5a607dc57eb)




3. Live Demo: Users can access a live demonstration of the Vehicle Detection and Counting System. This feature enables them to see the system in action, witness how it operates in real-time, and understand its capabilities.




![Screenshot (308)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/7cd086e3-0d0d-4cce-b4ad-882e5af7c269)




![Screenshot (305)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/99c54af2-8396-40bd-bfdf-ff176f466015)




4. Newsletter Subscription: To stay informed about the latest updates and developments related to the project, users have the option to subscribe to a newsletter. This feature ensures that users receive timely information about enhancements, new features, and relevant news.




![Screenshot (301)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/95c6fcc4-5217-4e08-bf48-7a786d72599c)




This website serves as a valuable platform for showcasing the practical applications of the system and provides a user-friendly interface for users to explore its functionalities and advantages in real-world scenarios.




![Screenshot (293)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/29860309-b4c8-4608-b7d8-469a4b90b442)




![Screenshot (299)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/7a3b158b-5140-4fba-aaeb-562c21e4f0ea)





![Screenshot (303)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System/assets/97623859/8157a577-0a78-472f-8576-07deb63db4cd)

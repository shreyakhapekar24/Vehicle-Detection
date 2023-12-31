# Vehicle Detection and Counting System

The Vehicle Detection and Counting System is a computer vision project implemented using the OpenCV library in Python. This system is designed to detect and count vehicles in real-time through video input, making it suitable for various traffic management and monitoring applications.


## What is OpenCV?

OpenCV is a Python open-source library, which is used for computer vision in Artificial intelligence, Machine Learning, face recognition, etc. In OpenCV, the CV is an abbreviation form of a computer vision, which is defined as a field of study that helps computers to understand the content of the digital images such as photographs and videos.
The purpose of computer vision is to understand the content of the images. It extracts the description from the pictures, which may be an object, a text description, and three-dimension model, and so on. For example, cars can be facilitated with computer vision, which will be able to identify and different objects around the road, such as traffic lights, pedestrians, traffic signs, and so on, and acts accordingly.


## Project Overview:

The Vehicle Detection and Counting System utilizes computer vision techniques to process video input and identify vehicles within the video frames. It employs background subtraction and contour detection to locate and count vehicles as they pass through a predefined area. Background Subtraction is used to identify moving vehicles (foreground) against a stationary background, while contour detection is employed to create bounding boxes around these vehicles for tracking and counting purposes. The system is capable of counting multiple vehicles simultaneously and provides real-time updates on the count.


## Functionalities:

1. Video Input: The system takes video input, which can be from a live camera feed or a pre-recorded video file.
2. Vehicle Detection: It employs the MOG (Mixture of Gaussians) background subtraction algorithm to detect moving objects, which are potential vehicles. The system distinguishes vehicles from the background by identifying regions with significant pixel intensity changes.
3. Contour Detection: Once potential vehicles are detected, the system applies contour detection to create bounding boxes around them. These bounding boxes outline the vehicles in the video frames.
4. Vehicle Counting: The system counts vehicles by tracking their movement across a predefined line within the video frame (defined by count_line_position). When a vehicle crosses this line, it is counted. The system ensures that it counts only valid vehicles based on predefined width and height thresholds.
5. Visual Feedback: The system provides visual feedback by drawing bounding rectangles around detected vehicles and displaying the vehicle count on the video frame. It also draws a counting line on the frame to visually represent the counting process.
6. Real-time Updates: The vehicle count is continuously updated in real-time and displayed on the video frame. This count can be used for various traffic management and monitoring purposes.
7. User Interaction: The system runs continuously until the user presses the Enter key (key code 13), after which it terminates the video feed and closes any open windows.





![Screenshot (287)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/52a33c30-a24d-4c14-820c-720c13248d0a)





![Screenshot (289)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/595797d1-124e-4809-9302-106fd3e72cc4)





## Algorithm Used: 

The primary algorithm used in this project is the MOG (Mixture of Gaussians) background subtraction algorithm. 
This algorithm is used for detecting moving objects in video sequences by modeling each background pixel as a mixture of Gaussians. It is commonly employed in video surveillance and motion detection applications.


## Applications:

The Vehicle Detection and Counting System has various applications, including:

1. Traffic management and monitoring
2. Toll booth automation
3. Parking lot occupancy monitoring
4. Security surveillance
5. Congestion detection and management





![Screenshot (295)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/45f40578-2042-4a03-869d-64881da38f23)





![Screenshot (296)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/73c4abbd-d01f-42d5-9e45-d5a863d6721c)





## Website Integration:

In addition to the Vehicle Detection and Counting System project, a dedicated website has been created to provide users with an interactive and informative experience. This website allows users to fully grasp the benefits and real-world applications of the project. 

Link to access the website: https://shreyakhapekar24.github.io/Vehicle-Detection-and-Counting-System-using-OpenCV/

Here are the key features and components of the integrated website:

1. Chat Support: The website includes a chat option that allows users to interact with a support representative or chatbot. Users can ask questions, seek assistance, or request additional information about the project.





![Screenshot (291)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/00aa008e-e8a1-432f-8fc2-c4add287a719)





2. Functionalities Showcase: The website comprehensively explains the functionalities of the system. Users can explore how it detects and counts vehicles, making it suitable for various traffic management and monitoring applications.





![Screenshot (298)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/3dc9847e-775d-46e0-abcb-382401c4f8af)





![Screenshot (309)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/30c3f0fd-d320-46cc-bb21-d524855757e6)





3. Live Demo: Users can access a live demonstration of the Vehicle Detection and Counting System. This feature enables them to see the system in action, witness how it operates in real-time, and understand its capabilities.





![Screenshot (308)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/79460d21-b1c0-41f8-8013-463c829c3315)





![Screenshot (305)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/59a294e9-2ffe-4f46-99db-8e762772cc06)





4. Newsletter Subscription: To stay informed about the latest updates and developments related to the project, users have the option to subscribe to a newsletter. This feature ensures that users receive timely information about enhancements, new features, and relevant news.





![Screenshot (301)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/da20fc11-93c2-4dd2-b3fb-ed937c096c01)





This website serves as a valuable platform for showcasing the practical applications of the system and provides a user-friendly interface for users to explore its functionalities and advantages in real-world scenarios.





![Screenshot (293)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/84927039-94c8-4907-a161-069a74172d93)





![Screenshot (299)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/79c1afca-e908-4000-86f3-17d01bf7a363)





![Screenshot (303)](https://github.com/shreyakhapekar24/Vehicle-Detection-and-Counting-System-using-OpenCV/assets/97623859/bf18b582-990d-4b5b-bf66-fb82d1ac2c8d)




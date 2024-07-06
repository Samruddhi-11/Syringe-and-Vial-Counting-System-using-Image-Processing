# Syringe-and-Vial-Counting-System-using-Image-Processing
![Screenshot (74)](https://github.com/Samruddhi-11/Syringe-and-Vial-Counting-System-using-Image-Processing/assets/114277670/eff27632-3f65-4d85-a8ff-1958332108a1)


This project aims to develop an automated system for counting syringes and vials using image processing techniques.
The system leverages machine learning and computer vision to accurately detect and count objects in images, 
enhancing inventory management efficiency.

Client: 
One of the leading pharmaceutical company in India.

Business Problem:
The challenge is to design a counting system for syringes and vials that streamlines operations and mitigates the risk of human error, ultimately optimizing productivity and accuracy in the process.

Business Objective:
Maximize efficiency and Minimize manual errors in inventory management.

Business Solution:
First I have collect research paper related to our problem and after that we collect image from Internet, all image are first week of syringes and vials. Then we annotate all image using object detection using roboflow because image are less then we use augmentation to increase the dataset. After that we use 5 pertained models for model, using transfer learning with the help of Robo flow and Python Streamlit libraries after that we check accuracy. And deploy model (Creating a user-friendly interface with Streamlit).   

Technology Stack: 
•	IDE: Google colab using GPU processor.
•	Annotation: Roboflow (Using Object detection).
•	Deployment Tools: Streamlit.

Business Benefits:
•	Minimize the manual effort by at least 10%.
•	Achieve an accuracy of at least 96%
•	Achieve a cost saving of at least SIM


Business Constraint:
Minimize the cost of solution.

Business success criteria:
Minimize the manual effort by at least 10%

Machine Learning success criteria: 
Achieve an accuracy of at least 96%

Economic success criteria:
Achieve a cost saving of at least SIM

model used:YOLOV8s
mAP (Mean Average Precision): 90.1%
epochs: 25
imgsz : 650

YOLOv8s (You Only Look Once, Version 8 - Small) :
A lightweight, fast, and efficient object detection model from the YOLO family, designed for real-time applications with limited computational resources.

Architecture : 

![Screenshot (73)](https://github.com/Samruddhi-11/Syringe-and-Vial-Counting-System-using-Image-Processing/assets/114277670/98f0360b-943c-401e-a170-2f9391795816)


OutPut:
![Screenshot (71)](https://github.com/Samruddhi-11/Syringe-and-Vial-Counting-System-using-Image-Processing/assets/114277670/92e4f76b-e02d-47cc-91f5-76e8af169fb4)
![Screenshot (70)](https://github.com/Samruddhi-11/Syringe-and-Vial-Counting-System-using-Image-Processing/assets/114277670/76ec1116-3d56-48ed-a7e4-6045db7e2d45)
![Screenshot 2024-06-20 162300](https://github.com/Samruddhi-11/Syringe-and-Vial-Counting-System-using-Image-Processing/assets/114277670/b150da93-3807-4356-bcfd-7923de2c96d8)


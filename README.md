# Face Recognition System with OpenCV: Hackathon Project

This repository contains the code and documentation for a face recognition system developed during a hackathon. The project aimed to create an efficient and accurate face recognition solution using the OpenCV library and machine learning techniques.

## Introduction
The face recognition system leverages the power of computer vision and machine learning to identify and classify individuals based on their facial features. The project involved two main components: the registration process and the login functionality.

## Registration Process
During the registration process, the system captured and stored facial images of users in a PostgreSQL database. The OpenCV library, along with trained Haarcascade files, was utilized to detect and extract facial parts from the images. These parts were then stored in the database, ensuring secure and efficient storage of the encoded facial data.

To enhance the performance of the face recognition model, image augmentation techniques were implemented. This involved applying various transformations to the captured images, creating a diverse set of inputs for better training and improved results. The model was continuously updated after each registration process, allowing it to adapt and improve its accuracy over time.

## Login Functionality
The login functionality of the system involved real-time face recognition. When an API was triggered with live captured images of a user, the system utilized the trained model to classify and match the captured image with existing user images stored in the database. The classification process achieved an impressive accuracy rate of 92%.

The accuracy of the face recognition model gradually improved as the system learned and updated itself with each registration process. The continuous adaptation of the model led to enhanced performance and better identification results over time.

## Key Features
- Face detection and extraction using Haarcascade files with OpenCV
- PostgreSQL integration for secure storage of encoded facial data
- Image augmentation techniques to improve the face recognition model's accuracy
- Real-time face recognition using the trained model
- Progressive learning and model updates after each registration process

## Usage
1. Clone the repository: `git clone https://github.com/Tatva-J/Swift-Buy.git`
2. Install the necessary dependencies: `pip install -r requirements.txt`
3. Set up the PostgreSQL database and configure the connection details in the code.
4. Run the registration script to capture and store user facial data.
5. Utilize the login functionality to classify and match live captured images with the stored user data.

## Conclusion
This face recognition system, developed as a part of a hackathon project, demonstrates the utilization of OpenCV and machine learning techniques for accurate and efficient identification of individuals based on their facial features. The project showcases the ability to integrate image processing, database management, and real-time recognition, making it a valuable contribution to the field of computer vision and biometric authentication.

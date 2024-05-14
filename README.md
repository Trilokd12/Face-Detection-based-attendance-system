# Face Recognition Based Attendance System

## Introduction
This project presents a Python-based attendance system that utilizes face recognition technology to record attendance. It features a user-friendly graphical user interface (GUI) designed with tkinter, making it accessible for users of all levels. The integration of OpenCV for image capturing and face recognition ensures efficient and accurate attendance tracking.

## Technologies Used
- **tkinter**: For crafting the entire GUI.
- **OpenCV**: Employed for capturing images and performing face recognition (`cv2.face.LBPHFaceRecognizer_create()`).
- **CSV, Numpy, Pandas, datetime**: Utilized for various backend operations such as data handling and time management.

## Features
1) **Interactive GUI**: An easy-to-navigate interface that simplifies the process of marking attendance.
2) **Password Protection**: Secure registration for new individuals with password verification.
3) **CSV Integration**: Automated creation and updating of CSV files containing student details upon registration.
4) **Daily Attendance Logs**: Generation of a new CSV file each day to record attendance with precise date and time stamps.
5) **Live Attendance Display**: Real-time updates of attendance shown on the main screen in a tabular format, including ID, name, date, and time.

## Setup and Installation
To set up the attendance system, follow these steps:
1. Ensure Python is installed on your system.
2. Install the required dependencies using pip:

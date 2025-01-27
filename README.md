Project Title:
Face Recognition with Excel-Driven Automation

Description:
This project implements a real-time face recognition system that automatically tracks attendance by recognizing faces and storing the data in an Excel spreadsheet. The system uses the face_recognition library for detecting and recognizing faces from live video feed, and openpyxl to handle the Excel file operations for attendance management.

Features:
Face Recognition: Identifies faces from a video stream and compares them with pre-stored known faces.
Attendance Tracking: Records the name and time of recognized faces and saves them in an Excel file.
Excel Integration: Automatically creates and updates an Excel file (Attendance.xlsx) with the recognized person’s name and the timestamp of their presence.
Real-time Processing: The system processes the video feed in real time and updates the attendance instantly.
Technologies Used:
Python: The main programming language used.
face_recognition: For face detection and recognition.
OpenCV: For video capture and real-time processing.
openpyxl: For handling Excel files.
NumPy: For numerical operations related to face recognition.

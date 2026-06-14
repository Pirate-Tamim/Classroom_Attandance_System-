📌 Classroom Attendance System – Facial Recognition :

Overview : 

This project is an AI-powered Classroom Attendance System that automates attendance marking using facial recognition. It detects faces, verifies students, and records attendance in real-time using Google Sheets.

🚀 Features

Facial Recognition: Uses face_recognition, OpenCV, and dlib to detect and verify students. 

Blink Detection: Ensures live presence using blink detection. 

Real-time Attendance: Automatically logs attendance in Google Sheets.

Optimized API Calls: Implements caching and request delay to avoid quota limits.

🛠️ Technologies Used :

Python – Core programming language for the project

OpenCV (cv2) – For image and video processing

face_recognition – For facial detection and recognition

dlib – For face landmark detection

NumPy (numpy) – For numerical computations and array operations

Pandas (pd) – For handling attendance data efficiently

Pickle (pickle) – For saving and loading face encoding data

Scipy (scipy.spatial.distance) – For calculating distances in blink detection

Google Sheets API (gspread) – For storing attendance records in Google Sheets

OAuth2Client (oauth2client.service_account) – For authentication with Google APIs

Datetime (datetime) – For recording timestamps of attendance

OS (os) – For handling file operations and directory management

Time (time) – For managing execution delays

📸 How It Works :

The system captures live video from the webcam.

Detects faces and verifies them with stored images.

Blink detection ensures live presence.

Marks attendance and updates Google Sheets.

🏆 Credits : 

Developed by Mahfuz Rahman Tamim 

AI Assistance by ChatGPT



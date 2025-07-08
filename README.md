Facial Recognition Attendance System (Demo)
A smart, contactless student attendance system powered by facial recognition and Google APIs.
This project was developed as part of an academic final-year project and is designed to streamline the attendance process using real-time face detection.

Note: Source code is kept private due to embedded sensitive API keys and service credentials (Google Sheets and Drive integration).

Project Overview
This system performs automated student attendance by:

Detecting faces via webcam

Matching them with stored student images

Logging entries to Google Sheets in real time

Storing backups locally in CSV format

[View Full Project Report (PDF)](./docs/FACIAL_RECOGNITION_ATTENDANCE_SYSTEM.pdf)

Includes architecture, workflow, screenshots, technology stack, and feature breakdown.

Features
Webcam-based face detection using OpenCV and face_recognition

Student registration through a Flask web interface

Google Sheets integration for cloud-based attendance logging

Google Drive API used to host and retrieve student photos

CSV backup for local attendance history

Role-based access (teacher/admin views)

Web dashboard with login, registration, and attendance table

Demo Screenshots (from /demo/ folder)
Login Page (/demo/sign-in.png)

Home Page (/demo/homepage.png)

Registration Form (/demo/registration.png)

Google Sheet Logging (/demo/sheet.png)

Attendance Table View (/demo/table_view.png)

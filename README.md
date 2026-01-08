# Automatic-Attendance-System-Harshithgraj
A robust, fixed-version Automatic Attendance System using face recognition, featuring enhanced camera handling, SQLite database, and a Tkinter GUI dashboard for employee registration, real-time scanning, reports, and Excel exports.

Biometric Attendance System
A comprehensive desktop application for real-time biometric attendance tracking using facial recognition technology. This project features enhanced camera handling, SQLite database integration, and an intuitive Tkinter GUI dashboard for seamless employee management, attendance scanning, reporting, and data export.

# Overview
This system is built to address real-world camera compatibility issues while providing a production-ready solution for educational institutions and corporate environments. The fixed version includes multi-backend camera support, robust error handling, and a user-friendly interface for administrators.

# Key Features
# Employee Registration & Management

Register employees with facial encoding and photo capture
Store employee details (ID, name, department, email, phone)
View employee list with photo preview functionality
Track employee registration dates and status

# Real-Time Attendance Scanning

Live face detection and recognition from webcam feed
Dual capture modes: Auto mode (automatic) and Manual mode (button-triggered)
Check-in/Check-out functionality with automatic duration calculation
Support for class, subject, and teacher tracking
Confidence scoring for recognized faces
Real-time attendance log display

# Advanced Camera Handling

Multi-backend camera support (DirectShow, MSMF, Auto-detection)
Automatic camera detection and enumeration
Camera testing utility for troubleshooting
Proper frame reading with fallback mechanisms
Error handling for camera initialization failures

# Comprehensive Reporting

View attendance logs with date filtering
Attendance summary with check-in/check-out times
Total hours calculation per session
Filter reports by date range, class, and subject

# Data Export

Export attendance data to Excel with professional formatting
Auto-column width adjustment
Summary sheets with clas
Timestamp and attendance status included

# Admin Dashboard

Quick action buttons for all major functions
Real-time statistics (Total Employees, Present Today, Absent Today)
Session management interface
Professional dark-themed UI with color-coded controls

# Technology Stack
Core Dependencies
OpenCV (cv2) - Image processing and camera capture
face_recognition - Facial encoding and comparison
NumPy - Numerical computations

# Database
SQLite3 - Lightweight relational database for data persistence

# User Interface
Tkinter - Python's standard GUI framework
PIL (Pillow) - Image processing for GUI display
ttk - Modern themed widgets for Tkinter

# Data Processing
Pandas - Data manipulation and SQL queries
openpyxl - Excel file generation and formatting

Additional
Threading - Non-blocking camera operations

# Installation
Prerequisites
Python 3.7 or higher

Webcam/camera device


# Security Considerations
Face Encodings: Stored as numerical vectors, not reversible to original images
Photo Storage: Registration photos stored as BLOB in database
Database: Store biometricattendance.db in secure location with restricted access
Camera Access: Ensure camera permissions are properly configured in OS
Data Export: Excel files contain sensitive attendance data - handle appropriately

# Performance Metrics
Face detection: ~30-50ms per frame (varies by resolution and GPU)
Face encoding: ~10-15ms per face
Face comparison: ~1-2ms per known face
Database operations: <100ms for typical queries
UI responsiveness: Threading prevents blocking during camera operations

# Future Enhancements
Multi-camera support for larger venues
Integration with attendance analytics dashboard
Email notifications for attendance alerts
Biometric template aging and retraining
Remote access via web interface
Integration with existing HR/payroll systems
Blockchain for attendance record immutability
Mobile app for employee self-service

Contributing
Contributions are welcome! Please:
Fork the repository
Create a feature branch (git checkout -b feature/amazing-feature)
Commit changes (git commit -m 'Add amazing feature')
Push to branch (git push origin feature/amazing-feature)
Open a Pull Request


Author
Harshith G Raj MBA Student, Alliance University
Focus: Business Analytics, AI Applications, Social Impact Technology

Acknowledgments
OpenCV community for robust computer vision library

dlib for facial recognition algorithms

Python community for excellent libraries and frameworks

Support & Feedback
For issues, feature requests, or questions:

Open an issue on GitHub

Include detailed error messages and steps to reproduce

Mention your Python version and OS

Last Updated: January 2026
Version: 1.0.0 (Fixed Camera Version)
Status: Production Ready

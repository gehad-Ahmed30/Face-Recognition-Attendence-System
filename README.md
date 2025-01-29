# 🎭 Face Recognition Attendance System
![Prject Photo](photos/Screenshot (89).png )
# 1)Hand Gesture Volume Control Project ✋🔊:-
![Prject Photo](photos/Screenshot (89).png )
## 🌟 Overview
The **Face Recognition Attendance System** is an AI-powered application 🤖 designed to automate attendance tracking 📋 using facial recognition technology. It utilizes **OpenCV, MediaPipe, Firebase, and face_recognition** to detect 👀 and recognize students' faces, record attendance ✅, and update a real-time database 📡.

## 🚀 Features
- **🎯 Real-Time Face Detection & Recognition**: Uses OpenCV and `face_recognition` to identify individuals.
- **📊 Automatic Attendance Logging**: Updates student attendance in Firebase based on recognition results.
- **🖼️ Profile Display**: Retrieves and displays student information, including name, major, and profile picture.
- **🔄 Mode-Based UI Updates**: Implements different display modes for detection, recognition, and attendance confirmation.
- **⏳ Time-Based Attendance Restriction**: Prevents multiple entries within 30 seconds to avoid duplicate records.
- **🎨 Customizable UI**: Overlays student details on a background image for better visualization.

## 🛠️ Technologies Used
- 🐍 **Python**
- 🖼️ **OpenCV** (Computer Vision)
- 🏷️ **face_recognition** (Face Detection & Encoding)
- 🔥 **Firebase Realtime Database** (Cloud Storage)
- ✋ **MediaPipe** (Hand & Face Tracking)
- 📊 **NumPy & Pickle** (Data Processing & Storage)

## ⚙️ How It Works
1. **📷 Face Detection**: The system captures a frame from the webcam and detects faces.
2. **🧬 Face Encoding & Matching**: Extracts facial features and compares them with known encodings.
3. **📌 Attendance Update**: If a face matches, the system updates the student's attendance in Firebase.
4. **📄 Display Student Details**: Retrieves and shows student information, including attendance history.
5. **🔄 UI Mode Switching**: Dynamically changes UI elements based on recognition status.

## 🔮 Future Enhancements
- 📱 **Mobile App Integration** for easier access.
- 👥 **Multi-Person Attendance** tracking.
- 📩 **Live Notifications** via SMS or email upon successful attendance.
- 🛡️ **AI-Powered Anti-Spoofing** to prevent fraudulent check-ins.

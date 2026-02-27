# attendance_system
# 🎓 AI-Based Attendance System

An intelligent **Face Recognition Attendance System** built using Python and Machine Learning to automate attendance marking through real-time camera detection.

---

## 📌 Project Overview

Traditional attendance methods are time-consuming and prone to proxy entries.
This project uses **Computer Vision + Machine Learning** to automatically detect, recognize, and mark attendance using a live camera feed.

The system captures student faces, trains a recognition model, and marks attendance when a registered face is detected.

---

## 🚀 Features

✅ Add new students with face capture
✅ Train face recognition model dynamically
✅ Real-time face detection using webcam
✅ Automatic attendance marking
✅ Attendance records stored in database
✅ Clean dashboard interface
✅ Prevents duplicate attendance entries
✅ Lightweight and runs locally

---

## 🛠️ Tech Stack

| Technology  | Usage               |
| ----------- | ------------------- |
| Python      | Backend Logic       |
| OpenCV      | Face Detection      |
| NumPy       | Image Processing    |
| Flask       | Web Framework       |
| SQLite      | Attendance Database |
| HTML/CSS/JS | Frontend UI         |

---

## 📂 Project Structure

```
attendance_system/
│
├── app.py                  # Main Flask application
├── model.py                # Face training & recognition logic
├── attendance.db           # SQLite database (auto-created)
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── index.html
│   ├── add_student.html
│   ├── mark_attendance.html
│   └── attendance_record.html
│
└── dataset/                # Captured face images (ignored in Git)
```

---

## ⚙️ How It Works

1️⃣ Add a student → system captures face images
2️⃣ Train model → builds recognition dataset
3️⃣ Start attendance → webcam detects faces
4️⃣ Recognized face → attendance marked automatically
5️⃣ Data saved into SQLite database

---

## 💻 Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/attendance_system.git
cd attendance_system
```

### 2️⃣ Create Virtual Environment

```
python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```
python app.py
```

Open browser:

```
http://127.0.0.1:5000
```

---

## 📊 Future Improvements

🔹 Deploy to cloud (AWS / Render)
🔹 Add Deep Learning (FaceNet / Dlib embeddings)
🔹 Multi-classroom support
🔹 Export attendance to Excel
🔹 Add Admin Authentication
🔹 Improve accuracy with CNN models

---

## 🎯 Use Cases

✔ Colleges & Schools
✔ Training Institutes
✔ Office Entry Monitoring
✔ Smart Classroom Systems

---

## 📸 Demo Workflow

Add Student → Train Model → Start Camera → Attendance Marked Automatically

---

## 👩‍💻 Author

**Neha Samanvitha**
B.Tech Computer Science Student
Aspiring AI/ML Engineer

---

## ⭐ If you found this useful, consider giving this repo a star!

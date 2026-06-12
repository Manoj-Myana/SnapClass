# 🎓 SnapClass - AI Attendance Tracker

SnapClass is an AI-powered attendance management system that automates student attendance using Face Recognition and Voice Recognition technologies. The platform provides dedicated dashboards for teachers and students, making attendance tracking faster, smarter, and more accurate.

## 🌐 Live Demo

**Deployed Application:** https://sc-landing-page-vert.vercel.app/

---

## 🚀 Features

### 👨‍🏫 Teacher Module

* Teacher Registration & Login
* Create and Manage Subjects
* Generate Subject Join Codes
* Share Subject Enrollment Codes
* Upload Classroom Photos
* AI-Based Face Recognition Attendance
* Voice Attendance Verification
* View Attendance Records
* Attendance Analytics Dashboard

### 👨‍🎓 Student Module

* Student Registration & Login
* Face-Based Authentication
* Join Subjects Using Subject Code
* View Enrolled Subjects
* View Attendance Status
* Automatic Attendance Updates

### 🤖 AI Features

#### Face Recognition Attendance

* Detects faces from uploaded classroom images
* Generates face embeddings using Dlib
* Matches students using a trained SVM classifier
* Automatically marks attendance

#### Voice Attendance

* Uses voice embeddings for speaker identification
* Supports attendance through audio recordings
* AI-powered voice verification and attendance logging

---

## 🛠️ Tech Stack

### Frontend

* Streamlit

### Backend

* Python

### Database

* Supabase

### Machine Learning & AI

* Dlib
* Scikit-Learn
* NumPy
* OpenCV
* Face Recognition Models
* Resemblyzer
* Librosa

### Additional Libraries

* Pandas
* Segno (QR Code Generation)

---

## 📂 Project Structure

```text
SnapClass
│
├── app.py
├── requirements.txt
│
├── src
│   ├── components
│   ├── database
│   ├── pipelines
│   ├── screens
│   └── ui
│
└── .streamlit
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/Manoj-Myana/SnapClass.git

cd SnapClass
```

### Create a Virtual Environment

```bash
python -m venv venv
```

### Activate the Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Setup

Create a `.streamlit/secrets.toml` file:

```toml
SUPABASE_URL="YOUR_SUPABASE_URL"
SUPABASE_KEY="YOUR_SUPABASE_KEY"
```

---

## ▶️ Running the Application

```bash
streamlit run app.py
```

The application will be available at:

```text
http://localhost:8501
```

---

## 📸 Face Recognition Workflow

1. Student registers using a facial image.
2. Face embeddings are generated using Dlib.
3. Embeddings are stored securely in Supabase.
4. Teacher uploads classroom images.
5. Faces are detected and compared against stored embeddings.
6. Attendance is marked automatically.

---

## 🎤 Voice Attendance Workflow

1. Student voice samples are stored.
2. Voice embeddings are generated.
3. Teacher uploads attendance audio.
4. AI identifies speakers.
5. Attendance records are updated automatically.

---

## 🔒 Security Features

* Teacher Authentication
* Student Authentication
* Subject Enrollment Validation
* Secure Supabase Backend
* AI-Based Attendance Verification

---

## 🌟 Future Enhancements

* Mobile Application
* Real-Time Attendance Monitoring
* Attendance Reports Export (PDF/Excel)
* Email Notifications
* SMS Notifications
* Multi-Classroom Support
* Advanced Analytics Dashboard
* Cloud-Based Face Recognition Services

---

## 💡 Key Highlights

✅ AI-Powered Face Recognition Attendance

✅ Voice-Based Attendance Verification

✅ Teacher & Student Dashboards

✅ Subject Management System

✅ QR Code-Based Subject Enrollment

✅ Cloud Database Integration with Supabase

✅ Modern and Interactive User Interface

---

## 👨‍💻 Author

**Manoj Myana**

GitHub: https://github.com/Manoj-Myana

LinkedIn: [Add your LinkedIn profile here](https://www.linkedin.com/in/manojkumarmyana16/)

---

## 📄 License

This project is developed for educational and learning purposes.

Feel free to use, modify, and enhance it for academic and research projects.

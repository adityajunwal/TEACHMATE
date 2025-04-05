# TeachMate – AI-Powered Teaching Assistant 🚀  
_Revolutionizing classrooms with AI-driven automation for teachers._

---

## 📌 Project Overview

**TeachMate** is an AI-powered assistant designed to automate and simplify tasks for teachers, such as grading, attendance tracking, student performance analysis, and classroom announcements.

---

## 🔹 Key Features

- ✅ **Automated Attendance** (Face Recognition, QR, Voice Commands)  
- ✅ **AI-Powered Grading** (Handwritten & Typed Answer Checking)  
- ✅ **Class Performance Dashboard** (Insights & Reports on Student Progress)  
- ✅ **AI-Generated Announcements** (WhatsApp, Email, In-App Notifications)  
- ✅ **Assignment & Test Management** (Auto-Grading & Scheduling)  
- ✅ **AI-Suggested Teaching Actions** (Personalized Student Support)

---

## 🏗 Tech Stack

- **Frontend:** React.js, Tailwind CSS  
- **Backend:** FastAPI / Flask  
- **Database:** PostgreSQL  
- **AI Services:**  
  - Gemini API (Grading, Performance Insights)  
  - Google Vision API (OCR for Handwritten Answer Checking)  
  - Face Recognition API (Automated Attendance)  
- **Deployment:** Vercel (Frontend), Render (Backend)

---

## 📁 Project Structure

```
TeachMate/
│
├── frontend/                # React.js frontend
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # Main app pages (Dashboard, Attendance, Assignments)
│   │   ├── api/             # API calls (Backend integration)
│   ├── public/              # Static assets
│   ├── package.json         # Frontend dependencies
│   └── .env                 # Frontend environment variables
│
├── backend/                 # FastAPI/Flask backend
│   ├── models/              # Database models (Teachers, Students, Attendance, Grades)
│   ├── routes/              # API routes (Attendance, Grading, Announcements)
│   ├── services/            # AI integrations (Gemini API, Face Recognition, OCR)
│   ├── main.py              # Backend entry point
│   ├── requirements.txt     # Backend dependencies
│   └── .env                 # Backend environment variables
│
├── docs/                    # Documentation (API, Setup Guide)
├── README.md                # Project Overview
├── .gitignore               # Ignored files
└── LICENSE                  # Project license
```

---

## 🚀 Getting Started

### 📌 Prerequisites

- Node.js (Frontend)  
- Python 3.9+ (Backend)  
- PostgreSQL (Database)

---

### 📌 Installation Steps

#### 1️⃣ Clone the Repo

```bash
git clone https://github.com/your-username/TeachMate.git
cd TeachMate
```

#### 2️⃣ Set Up Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

#### 3️⃣ Set Up Frontend

```bash
cd frontend
npm install
npm start
```

---

## 📌 User Manual: How to Use TeachMate

### 🔹 Login & Dashboard Access

- Open the TeachMate web application.  
- Login using your teacher credentials.  
- Dashboard shows:  
  - Attendance Summary 📅  
  - Student Performance Insights 📊  
  - Assignments & Test Status 📝  
  - AI-Suggested Teaching Actions 🤖

---

### 🔹 Taking Attendance

> **Methods Supported:** Face Recognition / QR Code / Voice Commands

- Navigate to the **Attendance Section**  
- Choose your method:  
  - **Face Recognition** – Camera detects and marks attendance  
  - **QR Code** – Students scan their codes  
  - **Voice Command** – e.g., "Mark attendance for Class X"  
- Click **Submit**

---

### 🔹 AI-Powered Grading

- Go to **Assignments Section**  
- Upload handwritten or typed answers  
- Grading is done via Gemini API  
- Reports appear in **Student Reports Section**

---

### 🔹 Sending Announcements

- Navigate to **Announcements Section**  
- Type or dictate your message  
- Choose delivery: WhatsApp, Email, or In-App  
- Click **Send**

---

### 🔹 Performance Reports

- Open **Performance Dashboard**  
- See individual & class-wise analytics  
- AI suggests personalized improvements

---

## 📌 Key API Endpoints

| Method | Endpoint                      | Description                                      |
|--------|-------------------------------|--------------------------------------------------|
| POST   | `/api/attendance/mark`        | Mark attendance via Face Recognition/QR Code    |
| POST   | `/api/assignments/grade`      | AI grading of assignments/tests                 |
| POST   | `/api/announcements/send`     | Send announcements via WhatsApp/Email           |
| GET    | `/api/dashboard/performance`  | Get student performance analytics               |

---

## 🤝 Contributing

1. Fork the repo  
2. Create your branch: `feature-xyz`  
3. Commit changes: `git commit -m "Added feature"`  
4. Push and open a **Pull Request**

---

## 📜 License

**MIT License** – Open-source & free to use!

---

## 🎯 Why TeachMate?

- ✅ **Saves Teachers’ Time** – Automates attendance, grading & announcements ⏳  
- ✅ **Improves Student Engagement** – Personalized AI teaching 📚  
- ✅ **AI-Driven Insights** – Data-backed teaching decisions 📊

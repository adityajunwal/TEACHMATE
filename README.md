TeachMate – AI-Powered Teaching Assistant
🚀 Revolutionizing classrooms with AI-driven automation for teachers.

📌 Project Overview
TeachMate is an AI-powered assistant designed to automate and simplify tasks for teachers, such as grading, attendance tracking, student performance analysis, and classroom announcements.

🔹 Key Features:
✅ Automated Attendance (Face Recognition, QR, Voice Commands)
✅ AI-Powered Grading (Handwritten & Typed Answer Checking)
✅ Class Performance Dashboard (Insights & Reports on Student Progress)
✅ AI-Generated Announcements (WhatsApp, Email, In-App Notifications)
✅ Assignment & Test Management (Auto-Grading & Scheduling)
✅ AI-Suggested Teaching Actions (Personalized Student Support)

🏗 Tech Stack
Frontend: React.js, Tailwind CSS
Backend: FastAPI/Flask
Database: PostgreSQL
AI Services:

Gemini API (Grading, Performance Insights)

Google Vision API (OCR for Handwritten Answer Checking)

Face Recognition API (Automated Attendance)
Deployment: Vercel (Frontend), Render (Backend)

📁 Project Structure
bash
Copy
Edit
TeachMate/
│── frontend/                # React.js frontend
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # Main app pages (Dashboard, Attendance, Assignments)
│   │   ├── api/             # API calls (Backend integration)
│   ├── public/              # Static assets
│   ├── package.json         # Frontend dependencies
│   ├── .env                 # Frontend environment variables
│
│── backend/                 # FastAPI/Flask backend
│   ├── models/              # Database models (Teachers, Students, Attendance, Grades)
│   ├── routes/              # API routes (Attendance, Grading, Announcements)
│   ├── services/            # AI integrations (Gemini API, Face Recognition, OCR)
│   ├── main.py              # Backend entry point
│   ├── requirements.txt     # Backend dependencies
│   ├── .env                 # Backend environment variables
│
│── docs/                    # Documentation (API, Setup Guide)
│── README.md                # Project Overview  
│── .gitignore               # Ignored files  
│── LICENSE                  # Project license  
🚀 Getting Started
📌 Prerequisites
Node.js (Frontend)

Python 3.9+ (Backend)

PostgreSQL (Database)

📌 Installation Steps
1️⃣ Clone the Repo

sh
Copy
Edit
git clone https://github.com/your-username/TeachMate.git
cd TeachMate
2️⃣ Set Up Backend

sh
Copy
Edit
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
3️⃣ Set Up Frontend

sh
Copy
Edit
cd frontend
npm install
npm start
📌 User Manual: How to Use TeachMate
🔹 Login & Dashboard Access
Open the TeachMate web application.

Login using your teacher credentials.

Once logged in, the dashboard will display:

Attendance Summary 📅

Student Performance Insights 📊

Assignments & Test Status 📝

AI-Suggested Teaching Actions 🤖

🔹 Taking Attendance (Face Recognition / QR Code / Voice Commands)
Navigate to the Attendance Section.

Choose your preferred method:

Face Recognition: Students stand in front of the camera.

QR Code: Students scan their QR codes from their mobile devices.

Voice Commands: Speak "Mark attendance for Class X".

Click "Submit" to record attendance.

🔹 AI-Powered Grading
Go to the Assignments Section.

Upload student handwritten or typed answers.

The AI Grading System (Gemini API) will automatically evaluate the answers.

The graded assignments will be available in the Student Reports Section.

🔹 Sending Announcements
Open the Announcements Section.

Type or dictate your message.

Choose delivery method (WhatsApp, Email, or In-App Notification).

Click "Send" to notify students.

🔹 Checking Student Performance Reports
Navigate to the Performance Dashboard.

View individual and class-wise performance analytics.

AI-generated student improvement suggestions will be available.

📌 Key API Endpoints
Method	Endpoint	Description
POST	/api/attendance/mark	Mark student attendance using Face Recognition/QR Code
POST	/api/assignments/grade	AI-powered grading of assignments/tests
POST	/api/announcements/send	Send automated announcements via WhatsApp/Email
GET	/api/dashboard/performance	Fetch student performance insights
🤝 Contributing
1️⃣ Fork the repo
2️⃣ Create a branch (feature-xyz)
3️⃣ Commit changes (git commit -m "Added feature")
4️⃣ Push & open a PR

📜 License
MIT License – Open-source & free to use!

📧 Contact
📩 Email: your-email@example.com
🔗 LinkedIn: Your Profile

🎯 Why TeachMate?
✅ Saves Teachers’ Time – Automates attendance, grading & announcements ⏳
✅ Improves Student Engagement – AI-based personalized teaching 📚
✅ AI-Driven Insights – Data-driven teaching decisions 📊

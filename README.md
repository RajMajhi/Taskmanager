📘 Student Task Manager

A simple web-based task manager built with Python (FastAPI + SQLAlchemy) to help students organize assignments, deadlines, and daily tasks.

🚧 This project is currently under development.

🧠 Project Goal

To create a mobile-friendly web app where students can:

📝 Register and log in

📌 Add and manage their tasks

⏰ Track deadlines and completion status

📊 Stay organized and productive

🏗️ Project Structure
student_task_manager/
│
├── requirements.txt
├── README.md
│
└── Taskmanager/
    │
    ├── backend/
    │   ├── main.py
    │   ├── database.py
    │   ├── models.py
    │   └── routes/
    │       ├── tasks.py
    │       └── users.py
    │
    └── frontend/
        ├── static/
        ├── index.html
        ├── login.html
        └── dashboard.html
⚙️ Tech Stack
🖥 Backend

FastAPI

SQLAlchemy

SQLite

Uvicorn

🎨 Frontend

HTML

CSS

JavaScript

🚀 How to Run (Backend)
1️⃣ Create and Activate Virtual Environment

Windows

python -m venv .venv
.venv\Scripts\activate

Mac/Linux

python -m venv .venv
source .venv/bin/activate
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run the API
cd Taskmanager/backend
uvicorn main:app --reload
4️⃣ Open in Browser

Visit:

http://127.0.0.1:8000/docs

Interactive API documentation powered by FastAPI.

📌 Features Implemented

✅ User model & routes

✅ Task model & routes

✅ SQLite database integration

✅ Basic FastAPI backend structure

✅ Simple frontend pages (Login / Dashboard)

🛠️ Features Coming Next

🔐 User authentication (JWT login)

✏️ Task creation, editing & deletion

📊 Task status tracking (Complete / Pending)

📱 Mobile UI improvements

🔗 Frontend ↔ Backend integration

☁️ Deployment

📷 Example Workflow

Student registers

Logs in

Adds tasks

Views tasks on dashboard

Updates progress

💡 Development Notes

This is an educational and evolving project

Structure and features may change as the app grows

Contributions and suggestions are welcome

🤝 Contributing

Contributions are welcome!

Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

🧑‍💻 Authors

Raj Majhi
GitHub: @RajMajhi

Manoj Muglikar
GitHub: @manojmuglikar44-afk

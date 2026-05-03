Team Task Manager (Full-Stack Project)

🚀 Overview
This is a full-stack web application where users can create projects, assign tasks, and track progress with role-based access (Admin / Member).

Built using Django (backend) and HTML, Tailwind CSS, JavaScript (frontend).

---

🧩 Features

✅ Authentication
- User Signup & Login
- Secure session-based authentication

✅ Project Management
- Create projects
- Add/remove team members
- Admin role control

✅ Task Management
- Create tasks
- Assign tasks to users
- Update task status (To Do, In Progress, Done)
- Delete tasks

✅ Dashboard
- Total tasks
- Completed tasks
- Pending tasks
- Overdue tasks

✅ Role-Based Access
- Admin: Full control
- Member: Can manage only assigned tasks

---

🛠️ Tech Stack

Backend:
- Django
- Django REST Framework

Frontend:
- HTML
- Tailwind CSS
- JavaScript (Fetch API)

Database:
- PostgreSQL (Production - Railway)

Deployment:
- Railway

---

🌐 Live URL

👉 https://web-production-66d62.up.railway.app

---

📂 GitHub Repository

👉 (https://github.com/kavathiyaparth08-boop/team-task-manager.git)
---

⚙️ Setup Instructions (Local)

1. Clone repo
git clone <your-repo-link>

2. Navigate to project
cd team-task-manager

3. Create virtual environment
python -m venv venv

4. Activate venv
venv\Scripts\activate

5. Install dependencies
pip install -r requirements.txt

6. Run migrations
python manage.py makemigrations
python manage.py migrate

7. Run server
python manage.py runserver

---

⚙️ Environment Variables

Create a .env file and add:

DATABASE_URL=your_postgresql_url
SECRET_KEY=your_secret_key

---

🚀 Deployment (Railway)

- Connected GitHub repo
- Added PostgreSQL plugin
- Set environment variables
- Used Procfile:
  web: python manage.py migrate && gunicorn config.wsgi

---

📌 Notes

- Project follows REST API structure
- Uses PostgreSQL in production
- Proper validations and relationships implemented
- Fully deployed and working

---

👨‍💻 Author

Name: Kavathiya Parth
Email: parthkavathiya26@gmail.com

# 📝 Employee-Manager Feedback System

A **FastAPI + SQLite backend system** for managing employees and managers, with authentication, manager-employee mapping, and extendable feedback functionality.

---

## 🚀 Features

- ✅ Register as **Manager** or **Employee**
- ✅ Employees are linked to their **Manager**
- ✅ Secure **login** (hashed passwords)
- ✅ Managers can view their employees
- ✅ Role-based dashboard redirection (frontend handles this)
- ✅ Uses **SQLite** for database
- ✅ Modular structure with FastAPI routers

---

## ⚙️ Tech Stack

- 🐍 **FastAPI** — modern Python API framework
- 💾 **SQLite** — lightweight database
- 🔐 **passlib[bcrypt]** — for password hashing
- ⚡ **SQLAlchemy** — ORM
- 🌐 **Uvicorn** — ASGI server

---

## ⚡ Setup & Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/employee-manager-feedback.git
cd employee-manager-feedback/backend
python -m venv venv
# Activate:
# On Windows
venv\Scripts\activate
# On Mac/Linux
source venv/bin/activate


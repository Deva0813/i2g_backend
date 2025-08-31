# 📝 Notes App Backend (FastAPI)

This is the backend for the Notes App.  
It provides **authentication** and **CRUD APIs** for notes.

---

## 🚀 Features
- User authentication with JWT
- Create, Read, Update, Delete notes
- Token-based security
- CORS enabled for frontend usage

---

## ⚙️ Setup

### 1. Install dependencies
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --port 8000
```
### 2. ENV Configurations
```bash
DATABASE_URL="MONGODB_URL"
SECRET_KEY="i2global_assessment"
ALGORITHM="HS256"
ACCESS_TOKEN_EXPIRE_MINUTES="30"
```

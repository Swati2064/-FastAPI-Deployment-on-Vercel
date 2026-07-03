# 🚀 FastAPI Deployment on Vercel

A simple FastAPI application deployed on Vercel.

## 📌 Project Overview

This project demonstrates how to deploy a FastAPI application on Vercel using Python.

When the API is accessed, it returns a JSON response:

```json
{
  "message": "Live from production!"
}
```

---

## 🛠️ Tech Stack

- Python
- FastAPI
- Uvicorn
- Vercel

---

## 📁 Project Structure

```
.
├── code.py
├── requirements.txt
├── vercel.json
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/FastAPI-Vercel-Hello-World.git
```

Move into the project folder

```bash
cd FastAPI-Vercel-Hello-World
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application locally

```bash
uvicorn code:app --reload
```

Visit

```
http://127.0.0.1:8000
```

---

## 📡 API Endpoint

### GET /

Response

```json
{
    "message": "Live from production!"
}
```

---

## 🚀 Deployment

Deploy the project using Vercel.

```bash
vercel
```

---

## 📦 Requirements

- Python 3.10+
- FastAPI
- Uvicorn
- Vercel CLI (Optional)

---

## 📄 Files

### code.py

Contains the FastAPI application.

### requirements.txt

Lists the required Python packages.

### vercel.json

Configuration file for deploying to Vercel.

---

## 🎯 Future Improvements

- Add multiple API endpoints
- Request validation
- Database integration
- Authentication
- Docker support
- CI/CD pipeline

---

## 👨‍💻 Author

**Swati Jadhav**


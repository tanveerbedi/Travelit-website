# 🌍 Travelit Website

**Travelit** is a Django-based travel booking and exploration platform built to help users search, view, and book hotels seamlessly. The project includes user authentication, payment integration using Razorpay, image uploads for hotels, and an admin dashboard for hotel management.

---

## 🚀 Features

- 🏨 Hotel Listings with Images
- 🛒 Booking and Payment Integration (Razorpay)
- 🧾 Admin Dashboard to Add/Edit Hotels
- 👤 User Registration & Login System
- 📸 Image Upload via `ImageField`
- 📁 Media Management (Django Static & Media Settings)

---

## 🧑‍💻 Tech Stack

| Tech              | Usage                          |
|------------------|--------------------------------|
| **Python 3.12**  | Backend programming language   |
| **Django**       | Web framework                  |
| **Razorpay**     | Payment Gateway Integration    |
| **SQLite**       | Default database               |
| **HTML/CSS/JS**  | Frontend templates             |
| **Pillow**       | ImageField support in Django   |

---

## ⚙️ Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/tanveerbedi/Travelit-website.git
cd Travelit-website/travelit
```

### 2. Create and Activate Virtual Environment

```bash
python -m venv venv
# Activate it
# Windows (cmd)
venv\Scripts\activate
# PowerShell
venv\Scripts\Activate.ps1
# macOS/Linux
source venv/bin/activate
```

### 3. Install Required Packages

```bash
pip install django razorpay setuptools Pillow
```

---

## 🔧 Project Setup

### 4. Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create Superuser

```bash
python manage.py createsuperuser
```

### 6. Run the Server

```bash
python manage.py runserver
```

Visit the app in your browser: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 📂 Project Structure

```
Travelit-website/
🔹 env/               # (optional) old virtual environment
🔹 venv/              # virtual environment
🔹 travelit/          # Django project folder
    🔹 manage.py
    🔹 settings.py
    🔹 urls.py
    └︎ ...
🔹 README.md
```

---

## 📝 Notes

- Make sure `MEDIA_URL` and `MEDIA_ROOT` are configured in `settings.py`
- Image uploads require the Pillow library
- Razorpay keys should be securely managed in production

---

## 📸 Demo

▶️ [Click here to watch the demo video](https://drive.google.com/file/d/1hp0EH6aH0D-p81TY_oN9sgmBQYPS-QWn/view?usp=sharing)

> This video demonstrates the core functionality and interface of the Travelit website in action.

---

## 🧑‍🎓 Author

**Tanveer Singh Bedi**  
💼 LinkedIn: https://www.linkedin.com/in/tanveer-singh-bedi-a8b811177
📬 Email: tsbedi2604@gmail.com

---

## 📄 License

This project is licensed under the MIT License.

---

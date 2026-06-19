# 🏥 Healthcare Backend Assignment

A Django REST Framework (DRF) backend API for managing patient records with authentication and user-based access control.

---

## 🚀 Features

- User authentication required  
- Patient CRUD operations (Create, Read, Update, Delete)  
- User-specific data access  
- Secure REST APIs using Django REST Framework  

---

## 🛠️ Tech Stack

- Python  
- Django  
- Django REST Framework  
- SQLite  

---

## ⚙️ Setup

```bash
git clone https://github.com/scolarpath/healthcare-backend-assignment.git
cd healthcare-backend-assignment

python -m venv venv
venv\Scripts\activate   # Windows

pip install -r requirements.txt

python manage.py migrate
python manage.py runserver

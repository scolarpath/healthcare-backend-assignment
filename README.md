Healthcare Backend Assignment

A Django REST Framework (DRF) backend API for managing patient records with authentication and user-based access control.

 Features
User authentication required
Patient CRUD operations (Create, Read, Update, Delete)
User-specific data access
Secure REST APIs using Django REST Framework
🛠️ Tech Stack
Python
Django
Django REST Framework
SQLite
 Setup
git clone https://github.com/scolarpath/healthcare-backend-assignment.git
cd healthcare-backend-assignment

python -m venv venv
venv\Scripts\activate   # Windows

pip install -r requirements.txt

python manage.py migrate
python manage.py runserver
Authentication

All APIs require login.

Header:

Authorization: Token <your_token>
 API Endpoints
POST /api/login/
POST /api/register/
GET /api/patients/
POST /api/patients/
GET /api/patients/{id}/
PUT /api/patients/{id}/
DELETE /api/patients/{id}/
Author

Srushti Kolawale
GitHub: https://github.com/scolarpath

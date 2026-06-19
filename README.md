🏥 Healthcare Backend Assignment

A Django REST Framework (DRF) backend API for managing patient records with secure authentication and user-based access control.

✨ Key Features

#🔐 Secure user authentication required

🧾 Full CRUD operations for patient records

#👤 User-specific data isolation (each user sees only their data)

⚡ RESTful APIs built using Django REST Framework

🛡️ Protected endpoints using permissions


🛠️ Tech Stack

Python 3

Django

Django REST Framework

SQLite


⚙️ Project Setup
1. Clone Repository
git clone https://github.com/scolarpath/healthcare-backend-assignment.git
cd healthcare-backend-assignment
2. Create Virtual Environment
python -m venv venv
venv\Scripts\activate   # Windows
3. Install Dependencies
pip install -r requirements.txt
4. Run Migrations
python manage.py migrate
5. Start Server
python manage.py runserver
🔐 Authentication

All endpoints require authentication.

Header Format:
Authorization: Token <your_token>
📡 API Endpoints
Auth
POST /api/login/
POST /api/register/
Patients
GET /api/patients/
POST /api/patients/
GET /api/patients/{id}/
PUT /api/patients/{id}/
DELETE /api/patients/{id}/
👩‍💻 Author

Srushti Kolawale
🔗 GitHub: https://github.com/scolarpath

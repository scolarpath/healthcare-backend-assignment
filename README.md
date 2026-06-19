# Healthcare Backend API

## Overview

This project is a Healthcare Management Backend developed using Django REST Framework and PostgreSQL. It provides APIs for managing patients, doctors, and patient-doctor mappings with JWT authentication.

## Features

* User Registration
* User Login using JWT Authentication
* Patient Management
* Doctor Management
* Patient-Doctor Mapping
* PostgreSQL Database Integration
* Protected API Endpoints

## Technologies Used

* Python
* Django
* Django REST Framework
* PostgreSQL
* JWT Authentication (Simple JWT)
* Postman

## Installation

### Clone the project

```bash
git clone <repository-url>
cd healthcare_assignment
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file and add:

```env
SECRET_KEY=your_secret_key
DEBUG=True

DB_NAME=healthcare_db
DB_USER=postgres
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5433
```

### Apply Migrations

```bash
python manage.py migrate
```

### Run Server

```bash
python manage.py runserver
```

## API Endpoints

### Authentication

* POST `/api/auth/register/`
* POST `/api/auth/login/`

### Patients

* GET `/api/patients/`
* POST `/api/patients/`

### Doctors

* GET `/api/doctors/`
* POST `/api/doctors/`

### Mappings

* GET `/api/mappings/`
* POST `/api/mappings/`

## Authentication

All protected endpoints require a JWT Access Token in the Authorization header:

```text
Bearer <access_token>
```

## Database

PostgreSQL

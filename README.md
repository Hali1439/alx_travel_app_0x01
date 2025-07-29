
# 🧳 ALX Travel_App_0x01

This project is part of the ALX Software Engineering Backend track. It builds a RESTful API using Django and Django REST Framework to manage property listings and bookings.

---

## 🌐 Project Overview

The goal of this milestone is to implement robust API endpoints for Listings and Bookings, supporting full CRUD operations. The endpoints are designed using DRF's `ModelViewSet` and follow RESTful conventions under the `/api/` route. Swagger/OpenAPI will be integrated for easy documentation and testing.

---

## ✅ Task Completed

- [x] Duplicated `alx_travel_app_0x00` into `alx_travel_app_0x01`
- [x] Created ViewSets for `Listing` and `Booking`
- [x] Configured API URLs using DRF’s `DefaultRouter`
- [x] Developed serializers with nested relationships (`User`, `Review`)
- [x] Tested endpoints using Postman (`GET`, `POST`, `PUT`, `DELETE`)
- [ ] Integrated Swagger/OpenAPI for API documentation (coming up)

---

## 📁 Project Structure

```

alx\_travel\_app\_0x01/
├── listings/
│   ├── models.py
│   ├── views.py
│   ├── serializers.py
│   ├── urls.py
├── alx\_travel\_app/
│   └── urls.py
├── manage.py
└── README.md

````

---

## 🧩 API Endpoints

Base URL: `/api/`

| Method | Endpoint         | Description             |
|--------|------------------|-------------------------|
| GET    | `/listings/`     | List all listings       |
| POST   | `/listings/`     | Create a new listing    |
| GET    | `/listings/{id}` | Retrieve a listing      |
| PUT    | `/listings/{id}` | Update a listing        |
| DELETE | `/listings/{id}` | Delete a listing        |
| GET    | `/bookings/`     | List all bookings       |
| POST   | `/bookings/`     | Create a new booking    |
| GET    | `/bookings/{id}` | Retrieve a booking      |
| PUT    | `/bookings/{id}` | Update a booking        |
| DELETE | `/bookings/{id}` | Delete a booking        |

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.10+
- Django 5.x
- Django REST Framework
- Postman or any API client

### 🛠️ Setup

```bash
# Clone the repo
git clone https://github.com/yourusername/alx_travel_app_0x01.git
cd alx_travel_app_0x01

# Create virtual environment
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run the server
python manage.py runserver
````

---

## 🔍 Testing the API

Use **Postman** or **cURL** to test the following:

```bash
GET http://localhost:8000/api/listings/
POST http://localhost:8000/api/bookings/
```

---

## 📄 Future Improvements

* [ ] Swagger API docs (`drf-yasg`)
* [ ] JWT Authentication
* [ ] Role-based permissions (host/user separation)
* [ ] Booking availability validation

---



```

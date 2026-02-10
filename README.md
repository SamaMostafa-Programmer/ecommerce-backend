# E-Commerce Backend API

A scalable and secure backend system for managing an e-commerce product catalog.  
Built as part of **Project Nexus – ProDev Backend Engineering Program**.

---

## Features
- Full CRUD operations for Products and Categories
- JWT-based Authentication (Access & Refresh tokens)
- Advanced Filtering, Sorting, and Pagination
- Interactive API Documentation using Swagger
- PostgreSQL-ready, normalized database design

---

## Tech Stack
- **Django**
- **Django REST Framework**
- **PostgreSQL**
- **JWT Authentication (SimpleJWT)**
- **Swagger / OpenAPI (drf-yasg)**

---

## Installation & Setup

```bash
git clone https://github.com/SamaMostafa-Programmer/ecommerce-backend.git
cd ecommerce-backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
---

The API will be available at: http://127.0.0.1:8000/

---

Authentication

Obtain JWT Token:
POST /api/token/

Refresh Token:
POST /api/token/refresh/

---

API Endpoints

Products:
GET /api/products/
POST /api/products/

Categories:
GET /api/categories/
POST /api/categories/

Supports filtering, sorting, and pagination.

---

API Documentation

Swagger UI:
/swagger/

Provides interactive API exploration and testing.

---

Database Design

The ERD (Entity Relationship Diagram) is included in the project submission documentation and illustrates:

Product–Category relationships

Normalized schema design

Optimized structure for scalability

---

Demo

A demo video showcasing the API functionality and features will be provided in the submission.

---

Author

Sama Mostafa
Backend Developer

---

## License

This project is developed for educational purposes as part of the ProDev Backend Engineering Program.

---

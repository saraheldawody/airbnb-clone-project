# 🏡 Airbnb Clone - Backend

This is the backend for an **Airbnb Clone**. It helps users sign up, list properties, book stays, pay online, and leave reviews. This project is not finished yet — we are still working on it.

---

## 🚀 Project Goal

The goal is to build a strong backend system that supports:

- 👤 User accounts (signup, login, profile)
- 🏘️ Property listings (create, update, delete)
- 📅 Booking system (reserve homes, check-in/out)
- 💳 Payment system (make and track payments)
- 🌟 Reviews (users rate properties)
- ⚡ Fast and optimized performance

---

## 🛠 Features (Plan)

### 1. API Docs
- Uses **OpenAPI** to document all endpoints.
- Supports **REST API** with Django REST Framework.
- Supports **GraphQL** for flexible queries.

### 2. User Management
- Endpoints: `/users/`, `/users/{user_id}/`
- Register, log in, update profile, delete account.

### 3. Property Management
- Endpoints: `/properties/`, `/properties/{property_id}/`
- Add, edit, view, and delete property listings.

### 4. Booking System
- Endpoints: `/bookings/`, `/bookings/{booking_id}/`
- Book a property, update booking, cancel booking.

### 5. Payments
- Endpoint: `/payments/`
- Process and record payments for bookings.

### 6. Reviews
- Endpoints: `/reviews/`, `/reviews/{review_id}/`
- Post and manage user reviews on properties.

### 7. Performance
- Database indexing for faster access.
- Caching with Redis to reduce load.

---

## ⚙️ Tech Stack

- **Django** – Main web framework
- **Django REST Framework** – For REST APIs
- **GraphQL** – For flexible data queries
- **PostgreSQL** – For storing data
- **Celery** – For background tasks (like emails, payments)
- **Redis** – For caching and sessions
- **Docker** – To run the app in containers
- **CI/CD** – To test and deploy automatically

---

## 👥 Team Roles

- **Backend Developer** – Builds APIs and logic
- **DB Admin** – Designs and optimizes the database
- **DevOps** – Deploys and scales the app
- **QA Engineer** – Tests everything

---

## 📌 API Endpoints Plan

### 🧑 Users

```shell
GET /users/ POST /users/ GET /users/{user_id}/ PUT /users/{user_id}/ DELETE /users/{user_id}/
```


### 🏠 Properties
```shell
GET /properties/ POST /properties/ GET /properties/{property_id}/ PUT /properties/{property_id}/ DELETE /properties/{property_id}/
```
### 📆 Bookings

```shell
GET /bookings/ POST /bookings/ GET /bookings/{booking_id}/ PUT /bookings/{booking_id}/ DELETE /bookings/{booking_id}/
```

### 💳 Payments
```shell
POST /payments/
```

### 🌟 Reviews
```shell
GET /reviews/ POST /reviews/ GET /reviews/{review_id}/ PUT /reviews/{review_id}/ DELETE /reviews/{review_id}/
```

## 🚧 Setup Instructions (coming soon)

```bash
# Clone the project
git clone https://github.com/your-username/airbnb-clone-backend.git

# Move into the project folder
cd airbnb-clone-backend

# Set up your virtual environment, install dependencies, and run the app
# (We'll update this section when implementation starts)
```


---

## 🔁 CI/CD Pipeline

### What is CI/CD?

CI/CD stands for **Continuous Integration** and **Continuous Deployment**. It means that whenever we make changes to the code, the system will automatically:

1. **Test the code** to check if it works correctly.
2. **Build the app** (like putting all the pieces together).
3. **Deploy the app** to a server if everything is okay.

This helps us **catch bugs early**, **save time**, and **deliver updates faster**.

### Why CI/CD is important

- 🚀 Automates testing and deployment
- 🛡️ Makes the app more stable and reliable
- 🧪 Helps catch errors before going live
- 🔄 Speeds up updates and improvements

### Tools We Might Use

- **GitHub Actions** – For automation workflows (testing, deployment)
- **Docker** – For consistent environments
- **Docker Hub** – For storing Docker images
- **Heroku**, **Render**, or **AWS EC2** – For hosting the app

# Backend API Project

## Description
This is a RESTful API built using Node.js, Express, and MongoDB Atlas. It performs CRUD operations on user data.

## Base URL
https://your-app.onrender.com

## Endpoints

### Create User
POST /api/login

Body:
{
  "username": "AfamO",
  "password": "12345"
}

---

### Get All Users
GET /api/users

---

### Update User
PUT /api/users/:id

Body:
{
  "username": "NewName"
}

---

### Delete User
DELETE /api/users/:id

---

## How to Test

### Using Postman:
1. Open Postman
2. Enter endpoint URL
3. Choose method (POST, GET, PUT, DELETE)
4. Add JSON body if needed
5. Click Send

---

## Technologies Used
- Node.js
- Express
- MongoDB Atlas
- Mongoose
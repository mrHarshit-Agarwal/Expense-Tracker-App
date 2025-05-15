# 💸 Expense Tracker - Spring Boot REST API

A simple and secure RESTful API built with **Spring Boot** that allows users to track their income and expenses. It supports user registration and login with JWT authentication, CRUD operations for income and expense records, and expense categories.

---

## 🚀 Features

- User registration & login with **JWT authentication**
- Add, view, update, and delete **income and expense entries**
- Manage **expense categories**
- Built using **Spring Boot**, **Spring Security**, and **MySQL**

---

## 📦 API Endpoints

### 🔐 User Authentication

#### ✅ Register User  
`POST /users/register`

- **Request Body** (JSON):
```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "yourPassword"
}

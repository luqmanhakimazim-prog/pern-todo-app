# PERN Todo App

A full-stack Todo application built with PostgreSQL, Express, React, and Node.js.

## Features
- Create new todos
- View all todos
- Edit todo description using Bootstrap modal
- Delete todos

## Tech Stack
- **Database:** PostgreSQL
- **Backend:** Node.js, Express.js
- **Frontend:** React, Bootstrap 4

## Getting Started

### 1. Database Setup
Create the database and table in PostgreSQL:
```sql
CREATE DATABASE perntodo;

CREATE TABLE todo(
  todo_id SERIAL PRIMARY KEY,
  description VARCHAR(255)
);
```

### 2. Backend Setup
```bash
cd server
npm install
npm start
```
The server will run on `http://localhost:5000`.

### 3. Frontend Setup
```bash
cd client
npm install
npm start
```
The client will run on `http://localhost:3000`.

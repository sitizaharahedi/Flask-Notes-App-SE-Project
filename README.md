# Flask Notes App - Portfolio Project

A simple **Full-Stack Notes App** demonstrating backend and frontend skills.  
This project is for **portfolio purposes only** to showcase my work in **Python, Flask, SQLAlchemy, and Bootstrap**.

---

## Project Overview

- **Frontend:** HTML templates with **Bootstrap 4** for a responsive UI  
- **Backend:** Flask web application with **user authentication** and CRUD functionality  
- **Database:** SQLite (persistent storage for users and notes)  
- **Functionality:**  
  - User Sign Up, Login, Logout  
  - Add, Read, Delete notes (CRUD operations)  
  - Notes are **user-specific** (each user only sees their own notes)  
  - JavaScript integration for deleting notes without reloading the page  

This project highlights my ability to build **web applications, connect to a database, manage user sessions, and implement frontend-backend integration**.

---

## Tech Stack

**Backend:** Python, Flask, Flask-Login, Flask-SQLAlchemy, SQLite  
**Frontend:** HTML, Jinja2 templating, Bootstrap 4, JavaScript  

---

## Application Routes

| Method   | Endpoint        | Description                          |
|----------|----------------|--------------------------------------|
| GET/POST | /              | Home page: display & add notes       |
| POST     | /delete-note   | Delete a note (AJAX via JavaScript) |
| GET/POST | /login         | User login                           |
| GET      | /logout        | User logout                          |
| GET/POST | /sign-up       | User registration                    |

---

## Skills Highlighted

- Flask backend development  
- Database modeling and ORM with SQLAlchemy  
- User authentication and session management with Flask-Login  
- CRUD operations for notes  
- Frontend integration using Bootstrap and JavaScript  
- Project structuring and version control  

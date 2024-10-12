# Task Manager API

## Overview
A RESTful API for managing tasks, designed with FastAPI. It includes CRUD functionality, user authentication, and validation.

## Features
- **CRUD**: Create, read, update, and delete tasks.
- **Authentication**: User registration, login, and token-based authentication.
- **Validation**: Enforces data validation and error handling.

## Installation
1. Install dependencies: `pip install -r requirements.txt`
2. Run the API: `uvicorn main:app --reload`
3. Access API documentation at `localhost:8000/docs`.

## Technologies Used
- `FastAPI` for API framework
- `SQLite` for database
- `JWT` for authentication

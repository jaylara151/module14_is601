# Module 14 IS601 – BREAD Calculations App

## Overview
This project is a FastAPI application that implements full BREAD functionality for calculations. Users can register, log in, and manage their own calculation history through both the web interface and API routes.

BREAD stands for:

- Browse
- Read
- Edit
- Add
- Delete

Each calculation is tied to the logged-in user, so users can only access their own records.

---

## Features

- User registration and login
- Token-based authentication
- Add new calculations
- Browse saved calculations
- View one calculation in detail
- Edit existing calculations
- Delete calculations
- Validation for bad input
- Division-by-zero protection
- PostgreSQL database
- Docker and Docker Compose support
- Pytest test suite
- GitHub Actions workflow
- Docker Hub deployment

---

## Supported Operations

- Addition
- Subtraction
- Multiplication
- Division

---

## Tech Stack

- FastAPI
- PostgreSQL
- SQLAlchemy
- Pydantic
- Jinja2
- JavaScript
- Docker
- Pytest
- GitHub Actions

---

## GitHub Repository

`https://github.com/jaylara151/module14_is601`

---

## Docker Hub Repository

`https://hub.docker.com/r/jaylara/module14_is601`

---

## How to Run the App

### 1. Clone the repository
```bash
git clone git@github.com:jaylara151/module14_is601.git
cd module14_is601
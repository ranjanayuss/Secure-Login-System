# Secure Login System

## Overview

A secure authentication web application built using Flask, SQLite, and bcrypt.

## Features

- User Registration
- User Login
- Password Hashing (bcrypt)
- Session Management
- Logout Functionality
- SQL Injection Protection
- Input Validation

## Installation

```bash
pip install -r requirements.txt
```

## Run

```bash
python app.py
```

Open:

http://127.0.0.1:5000

## Security Features

- Passwords are hashed using bcrypt.
- Parameterized SQL queries prevent SQL injection.
- Session-based authentication.
- Basic validation for usernames and passwords.

## Technologies

- Python
- Flask
- SQLite
- bcrypt

## Educational Purpose

This project demonstrates secure authentication practices for web applications.

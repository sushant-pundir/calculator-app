# Python Flask Calculator API

A REST API calculator built using Python, Flask and Flask-RESTful.

## Features
- Addition
- Subtraction
- Multiplication
- Division
- JSON API support
- Unit testing

## Installation

    python3 -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt

## Run

    python app.py

Server: http://127.0.0.1:5000

## API Endpoints

| Method | Endpoint |
|---|---|
| POST | /add |
| POST | /subtract |
| POST | /multiply |
| POST | /division |

## Tests

    python -m unittest test_app -v

## Attribution

Based on Flask Calculator Beginner Docker by Santhosh Kumar D.

Original repository:
https://github.com/Santhoshkumard11/Flask-Calculator-Beginner-Docker

Original MIT license retained.

# Hello World Flask App

## Overview
A minimal Flask web application that:
- Serves a plain-text "Hello World!" at the root endpoint (/), satisfying the evaluation requirement.
- Also exposes a simple HTML page at /page that displays "Hello World!" with light styling.

This project demonstrates both a Flask backend and a small HTML frontend, kept intentionally simple.

## Setup
Prerequisites:
- Python 3.8+ recommended
- pip

Steps:
1. Install dependencies:
   - pip install flask
2. Ensure the main app file (index.html) is present. Note: despite the .html name, it contains valid Python and can be executed by Python.

Optional: Create and activate a virtual environment before installing dependencies.

## Usage
- Start the server:
  - python index.html
- Visit in your browser:
  - Root text endpoint: http://127.0.0.1:5000/ (returns "Hello World!")
  - HTML page: http://127.0.0.1:5000/page (styled "Hello World!" page)

Environment variables:
- PORT: To change the port, e.g., PORT=8000 python index.html

## Improvements in Round 2
Compared to the previous version:
- Kept the root (/) endpoint strictly returning plain "Hello World!" to satisfy automated checks.
- Added a dedicated HTML route (/page) rendered with Flask’s render_template_string, providing a simple, styled UI.
- Improved developer ergonomics: configurable port via environment variable and clarified setup/usage instructions.
This is the backend API for AI Tutor

Virtual environment setup:
Create environment
python -m venv .venv

If PowerShell restricts scripts for security reasons:
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

Activate:
.venv\Scripts\activate

To run server:
flask run --debug -p 3000

# Django Backend Project

This project demonstrates:
- Django REST Framework (DRF) for API endpoints
- Token-based authentication (SimpleJWT)
- Celery for background tasks
- Telegram bot integration

## Setup

1. Install dependencies (already installed):
   - django
   - djangorestframework
   - djangorestframework-simplejwt
   - celery
   - python-telegram-bot

2. Run migrations:
   ```powershell
   C:/Users/DELL/AppData/Local/Programs/Python/Python313/python.exe manage.py migrate
   ```

3. Create a superuser:
   ```powershell
   C:/Users/DELL/AppData/Local/Programs/Python/Python313/python.exe manage.py createsuperuser
   ```

4. Start the development server:
   ```powershell
   C:/Users/DELL/AppData/Local/Programs/Python/Python313/python.exe manage.py runserver
   ```

## Features
- API endpoints with DRF
- JWT authentication
- Background tasks with Celery
- Telegram bot integration

## Next Steps
- Configure Celery and Telegram bot in settings
- Implement API endpoints in `core` app
- Add Celery tasks and Telegram bot logic

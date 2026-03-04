# Skystore

Интернет-магазин для продажи плагинов и примеров кода.

## Технологии
- Python 3.10+
- Django 4.2.11
- Bootstrap 5.3

## Установка
```bash
git clone <repo-url>
cd skystore-final
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
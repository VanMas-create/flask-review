# Flask Review
Учебный Flask-проект для лабораторной работы 2 по дисциплине "Инструменты разработки".

## Требования
Python 3.15+

## Установка
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install -r requirements.txt

## Запуск сервера
    python app.py

Откройте http://127.0.0.1:8080

## Запуск тестов
    python -m pytest -q

## Доступные URL

- `/` — Hello, World!
- `/about` — текстовое описание проекта
- `/health` — JSON {"status":"ok"}
# Flask Review — версия первой ветки

Учебное Flask-приложение для лабораторной работы №2.

## Требования
Python 3.15

## Установка
python -m venv .venv
source .venv/Scripts/activate
python -m pip install -r requirements.txt

## Запуск сервера
python app.py

## Запуск тестов
python -m pytest -q

## Доступные маршруты

- `/` — главная страница приложения.
- `/about` — информация о проекте.
- `/health` — проверка состояния приложения, возвращает JSON `{"status": "ok"}`.

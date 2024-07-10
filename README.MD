# Новостной портал

Новостной сайт

## Описание
Сайт создан с использованием микрофреймворка Flask

## Технологии
* Python
* Flask
* WTForms
* SQLAlchemy

## Как запустить
1. Склонируйте репозиторий
2. Создайте и активируйте виртуальное окружение
```commandline
python -m venv venv
source venv/Scripts/activate
```
3. Установите зависимости
```commandline
pip install -r requirements.txt
```
4. Создайте файл .env и укажиите настройки подключения к БД и другие параметры.
```commandline
DATABASE_URI=sqlite:///db.sqlite
SECRET_KEY=YOUR_SECRET_KEY
```
5. Запустите flask приложение
```commandline
flask run
```
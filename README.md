# Описание проекта "Приложение, которое является агрегатором данных из access логов веб-сервера Apache с сохранением в БД"

Этот проект представляет собой приложение, где пользователь может посмотреть отпаршеный access.log, отфильтровать его по Ip, по промежутку дат и по ip в промежутке дат. В проекте используется язык программирования Python и фреймворк Flask.

## Установка и запуск проекта

1. Склонируйте репозиторий на свой локальный компьютер:

git clone https://github.com/username/blog.git


2. Установите необходимые зависимости:

pip install tkinter
pip install ttkbootstrap
pip install requests
pip install pymysql
pip install flask

3. Запустите проект:

python main.py


4. Откройте браузер и перейдите по ссылке http://Ваш_публичный_айпи:5000/logs

## Описание структуры проекта

Папка program:
- `main.py` - файл запуска приложения.
- `config.py` - файл конфигурации.
- `login.py` - файл в котором окно входа пользователя.
- `register.py` - файл в котором окно регистрации пользователя.
- `user.py` - основной файл приложения.

Папка program/bd:
- `AccessLogi.db` - база данных, куда записывается данные из API.

Папка api:
- `api.py` - наше API для сервера.

## Описание функционала приложения

- Главная страница отображает список всех спаршенных access.log.
- Во вкладке 'Фильтр' находятся предлагаемые нами фильтры.
- Во вкладке 'Фильтр/Фильтр по ip' вы можете отфильтровать данные по ip.
- Во вкладке 'Фильтр/Фильтр по start_date и end_date' вы можете отфильтровать данные по промежтку дат.
- Во вкладке 'Фильтр/Фильтр по всем' вы можете отфильтровать данные по ip и по промежтку дат.

## Технологии, используемые в проекте

- Python
- Flask

## Авторы

- Панченко Максим
- Артём Тарасовский

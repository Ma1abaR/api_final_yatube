##Описание
API для социальной сети, в которой пользователи могут публиковать записи и просматривать сообщения других пользователей. Реализованы механизм комментариев к записям, возможность подписки на публикации интересующий авторов, регистрация пользователей. Для аутентификации используется JWT-токен.

##Технологии:
Python3, Django, DjangoORM, Django REST Framework, SQLite

#Запустить проект можно следующим образом:

### 1) Склонировать репозиторий:
Клонируйте репозиторий и перейдите в него в командной строке:
git clone
cd api_final_yatube

### 2) Создать и активировать виртуальное окружение для проекта
Cоздайте и активируйте виртуальное окружение:
python3 -m venv venv
либо для Windows:

python -m venv venv
затем:

source venv/bin/activate
либо для Windows:

venv\Scripts\activate либо venv\Scripts\activate.bat
Обновите pip:
python3 -m pip install --upgrade pip

### 3) Установить зависимости из файла requirements.txt:
Установите зависимости из файла requirements.txt:
pip install -r requirements.txt

### 4) Сделать миграции
Выполните миграции:
python3 manage.py migrate

### 5) Запустить сервер
Запустите проект:
python3 manage.py runserver


#Документация:

http://127.0.0.1:8000/redoc/

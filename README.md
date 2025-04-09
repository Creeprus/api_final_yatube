# Описание

Проект обращается к сервису Yatube посредством API и позволяет отправлять запросы на публикации: записей, комментариев, а также подписываться и отписываться от других авторов.

# Установка

1. Клонирование проекта

git clone https://github.com/Creeprus/api_final_yatube

cd api_final_yatube (Linux) или открыть bash терминал в папке api_final_yatube (Windows)

2. Активирование виртуального окружения

python3 -m venv env
source env/bin/activate
python3 -m pip install --upgrade pip

3. Установка зависимостей 
pip install -r requirements.txt

4. Выполнение миграций

python3 manage.py migrate

5. Запуск 
python3 manage.py runserver

# Примеры
http://127.0.0.1:8000/redoc/ - начальная страница

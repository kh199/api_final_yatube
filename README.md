# REST API для проекта Yatube

Реализация программной части API для проекта в соответствии с документацией.

Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/kh199/api_final_yatube
```

Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
source env/bin/activate
```

Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

Выполнить миграции:
```
python3 manage.py migrate
```

Запустить проект:
```
python3 manage.py runserver
```
По адресу http://127.0.0.1:8000/redoc/ доступна документация для API Yatube


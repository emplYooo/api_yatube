# api_final

## Автор:
Дмитрий Евстратов


## Описание:
api final - это REST API для блог-платформы Yatube. Позволяет просматривать и отправлять посты, просматривать группы, подписываться на авторов.

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone clone git@github.com:emplYooo/api_final_yatube.git
```

```
cd /c/API
```

Cоздать и активировать виртуальное окружение:

```
py -m venv venv
```

```
source venv/Scripts/activate 
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

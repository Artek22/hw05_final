# Yatube

### Описание проекта:

Социальную сеть для публикации личных дневников. 
Это сайт, на котором можно создать свою страницу. Если на нее зайти, то можно посмотреть все записи автора.
Пользователи смогут заходить на чужие страницы, подписываться на авторов и комментировать их записи. 
Автор может выбрать имя и уникальный адрес для своей страницы. 

### Как запустить проект на тестовом сервере:
Клонировать репозиторий, перейти в директорию с проектом.

```
git@github.com:Artek22/hw05_final.git
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/source/activate
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py makemigrations
```
```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

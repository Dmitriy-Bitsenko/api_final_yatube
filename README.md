# Описание проекта «API для Yatube»
Проект API для социальной сети Yatube

# Установка
Клонировать репозиторий и перейти в него в командной строке:

```
https://github.com/Dmitriy-Bitsenko/api_final_yatube.git
```
Перейти в директорию:
```
cd yatube_api
```
Cоздать виртуальное окружение:
```
python -m venv venv
```
Активировать окружение:
```
source venv/Scripts/activate
```
Установить зависимости из файла requirements.txt
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

# Примеры запросов к API
GET запрос, список всех постов:
```
/api/v1/posts/
```
POST запрос, список всех постов:
```
/api/v1/posts/
```
GET запрос, детальная информация о посте:
```
/api/v1/posts/{post_id}/
```
POST запрос, заменить пост:
```
/api/v1/posts/{post_id}/
```
PATCH запрос, обновить пост:
```
/api/v1/posts/{post_id}/
```
DELETE запрос, удалить пост:
```
/api/v1/posts/{post_id}/
```
# Используемые технологии:
Python 3.12, Django 3.2.16, DjangoRestFramework 3.12.4, djoser 2.1.0

# Автор:
Биценко Дмитрий



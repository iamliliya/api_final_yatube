# API Yatube final

### Описание
**API для моделей приложения Posts проекта Yatube**

### Установка
Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/iamliliya/api_final_yatube.git
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
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
В проекте доступны энпоинты для взамодействия с моделями приложения Posts.

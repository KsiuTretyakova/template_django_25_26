# Template Django Project

## Структура проєкту
```commandline
template_django
|
⊢ app
    |
    ⊢ migrations
        ⨽ __init__.py
    |
    ⊢ __init__.py
    ⊢ admin.py
    ⊢ apps.py
    ⊢ models.py
    ⊢ tests.py
    ⨽ views.py
|
⊢ media
|
⊢ project
    ⊢ __init__.py
    ⊢ asgi.py
    ⊢ settings.py
    ⊢ urls.py
    ⨽ wsgi.py
|
⊢ static
    |
    ⊢ css
        ⨽ styles.css
    |
    ⊢ img
    |
    ⨽ js
        ⨽ script.js
|
⊢ templates
    ⨽ index.html
|
⊢ manage.py
⊢ README.md
⨽ requirements.txt
```

1. Встановити (або активувати) віртуальне середовище.
2. Встановити залежності  
```pip install -r requirements.txt```
другий метод  
```uv pip install -r requirements.txt```
3. 
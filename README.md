#  Отчёт
1. [Поиск подходящего проекта](#1)
2. [Установка и настройка](#2)


## [Поиск подходящего проекта](#1)
За основу был взят проект [simple-django-login-and-register](https://github.com/egorsmkv/simple-django-login-and-register)

Вместо Poetry было использовано обычное создание виртуального окружения и установка зависимостей из файла requirements.txt

### Проверка на работоспособность:
```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

![Проверка на работоспособность](report/1.png)

## Настройка nginx
# Django-auth

## Описание

Стандартная система аутентификации на Django: регистрация, вход, выход, профиль пользователя и главная страница.

## Быстрый старт

1. Клонируйте репозиторий:
   ```
   git clone https://github.com/Alexd1006/Django-auth.git
   cd Django-auth
   ```
2. Создайте и активируйте виртуальное окружение:
   ```
   python -m venv venv
   venv\Scripts\activate  # Windows
   source venv/bin/activate  # Linux/Mac
   ```
3. Установите зависимости:
   ```
   pip install django
   pip install python-dotenv
   ```
4. Примените миграции:
   ```
   python manage.py migrate
   ```
5. Запустите сервер:
   ```
   python manage.py runserver
   ```

## Пример .env (если используется)

```
SECRET_KEY=ваш_секретный_ключ
DEBUG=True
ALLOWED_HOSTS=127.0.0.1,localhost
```

## Контакты

Автор: Alexd1006
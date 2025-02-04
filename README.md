# API для Yatube

## Описание
Этот проект представляет собой RESTful API для социальной сети Yatube. API позволяет пользователям взаимодействовать с постами, комментариями, группами и подписками. Основные возможности:
- Создание, чтение, обновление и удаление постов.
- Добавление и управление комментариями к постам.
- Просмотр групп и их описаний.
- Подписка на других пользователей и управление подписками.

API использует JWT-аутентификацию для защиты эндпоинтов и предоставляет доступ к данным в формате JSON.

## Установка

1. **Клонируйте репозиторий**:
   ```bash
   git clone https://github.com/DarKingRD/api_final_yatube.git
   cd api_final_yatube
   ```
2. Создайте и активируйте виртуальное окружение:
  ```bash
  python -m venv venv
  source venv/bin/activate  # Для Linux/MacOS
  venv\Scripts\activate     # Для Windows
  ```
3. Установите зависимости:
  ```bash
  pip install -r requirements.txt
  ```
4. Примените миграции:
  ```bash
  python manage.py migrate
  ```
5. Запустите сервер:
  ```bash
  python manage.py runserver
  ```
## Документация API
После запуска сервера документация будет доступна по адресу:
http://127.0.0.1:8000/redoc/

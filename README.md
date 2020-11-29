# Проект "Yamdb"

Командная работа над API для проекта Yamdb. Учебный проект представляет собой DRF API приложение базы отзывов о фильмах, книгах и музыке с пройденым код ревью. 

Реализовано:
- Пользовательские роли(Администратор, модератор, аутентифицированный пользователь, аноним)
- Алгоритм регистрации пользователей(email, JWT-токен) 
- Возможность получать в JSON-формате: Категории, Жанры, Комментарии, Ревью

Стек технологий:
- Python
- Django
- Django REST Framework

# Развертывание проекта

1. python manage.py createsuperuser #Создание супер пользователя
2. python manage.py makemigrations python manage.py migrate #Выполнение миграций
3. pip install -r requirements.txt #Установка всех пакетов
4. python manage.py runserver #Запуск сервера
5. Либо запуск через Docker docker-compose up

Документация по API Yamdb: http://localhost:8000/redoc/

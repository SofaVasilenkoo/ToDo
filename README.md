# ToDo

Этот проект представляет собой простое веб-приложение для создания, управления и отслеживания задач, построенное на базе Django. Приложение позволяет пользователям зарегистрироваться, войти в систему, создавать задачи, назначать их сроки выполнения, отмечать задачи как выполненные и устанавливать приоритеты для каждой задачи. Каждый пользователь видит только свои собственные задачи.

## Установка и запуск

1. Клонируем репозиторий
   
   `git clone https://github.com/SofaVasilenkoo/ToDo.git`

2. Создаем виртуальное окружение

   `python3 -m venv venv`

   Активируем виртуальное окружение на Windows: `venv/Scripts/activate`

   На MacOS и Linux:   `source venv/bin/activate`
   
3. Установим зависимости

   `pip install -r requirements.txt`
   
4. Запустим сервер

   `python manage.py runserver`

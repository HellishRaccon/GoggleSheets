Инструкция по запуску скриптов

Создать виртуальное окружение с помощью комманд
    pip install virtualenv
    virtualenv -p project/venv

Активировать виртуальное окружение
    .\venv\Scripts\activate.ps1

Установить необходимые библиотеки
    pip install requirements.txt

Скрипт test_telegram.py
    Описание:
        Скрипт служит для регистрации получателя уведомлений в телеграмм, с помощью выполнения стартовой комманды(/start)
    
    Запуск:
        Запустить скрипт
        Подписаться на бота в телеграмме (@Test_Google_Sheets_bot)
    
    Опционально:
        Если больше подписчиков не ожидается, можно убить процесс

Скрипт main.py
    Описание:
        Основной скрипт. Служит для получения данных из Google Sheets и отправки в базу данных. Так же проверяет не прошел ли срок поставки, если прошел, то отправляет уведомление в телеграмм с номером заказа.
    
    Запуск:
        Запустить скрипт

Базу данных можно посмотреть по адрессу (https://test-google-sheets-rjazanov.herokuapp.com/admin/)
    Логин: admin
    Пароль: admin
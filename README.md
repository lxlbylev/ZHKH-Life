# ЖКХ-Лайф

ЖКХ-Лайф - это мобильное приложение, предназначенное для упрощения взаимодействия жителей многоквартирных домов с управляющими компаниями и органами ЖКХ.
Особенности приложения

* Удобный доступ к информации об услугах ЖКХ, которые доступны жителям;
* Уведомления об изменениях в расписании работы управляющей компании и перерывах в подаче коммунальных услуг;
* Доступ к истории оплат и возможность просмотра текущего состояния баланса;
* Функция "Обратная связь", которая позволяет жителям отправлять отзывы об управляющей компании.
* Отображение количества жильцов приближенное к реальным цифрам.

# Технологии

Приложение разработано с использованием следующих технологий:
* Фронтенд приложение реализовано с помощью фреймворка Solar2D, использующего язык Lua;
* Бэкенд приложения реализован на фреймворке Laravel, использующем язык PHP;
* Для хранения данных используется база данных MySQL.

# Установка

Для установки приложения необходимо скачать APK-файл из репозитория и установить его на мобильном устройстве. Для этого следуйте инструкциям:

* Скачайте APK-файл из репозитория на свое мобильное устройство;
* Откройте на устройстве меню "Настройки";
* Найдите пункт "Безопасность" и нажмите на него;
* Включите опцию "Неизвестные источники";
* Откройте файловый менеджер на устройстве и найдите загруженный APK-файл;
* Нажмите на файл и следуйте инструкциям установщика;
* После завершения установки, вы сможете найти приложение на своем мобильном устройстве в меню приложений.

---
Для установки сервера необходимо:

Склонируйте репозиторий на свой компьютер

    git clone https://github.com/yourusername/zhkh-life.git

Установите необходимые зависимости

    cd zhkh-life
    composer install

Создайте базу данных MySQL и заполните ее тестовыми данными

    mysql -u username -p zhkh-life < database/zhkh-life.sql

Настройте файл .env с данными для подключения к базе данных

    cp .env.example .env

Запустите приложение на локальном сервере

    php artisan serve

Откройте сервер в браузере по адресу http://localhost:8000

# Команда разработчиков

* Христолюбов Лев - Mobile-разработчик
* Кондратьев Владимир - GIS-разработчик
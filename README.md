Проект "Сайт автосалона"
------------------------
----------

> **Используемое ПО:**

> - Nginx;
> - Apache;
> - PHP 7.

#### Установка и настройка сайта

 1. Скачать весь репозиторий;
 2. Настроить веб-сервер (Apache, Nginx и т. д.) на папку **web**.

#### Настройка и проведение тестирования
 1. Изменить в файле **tests/acceptance.suite.yml** строку `url: http://car-showroom.ru`на адрес Вашего сайта;
 2. Находясь в папке сайта, выполнить команду `alias cept="./vendor/bin/codecept"`;
 3. Выполнить команду `cept build`;
 4. Выполнить команду `cept run`.

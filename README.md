# joomla-dev

Проект настройки Docker для разработки joomla

# Запуск сервисов на docker

У Вас должен быть установлен docker и docker-compose

Запустить docker-compose из папки проекта командой docker-compose up -d

Важно! После запуска необходимо немного подождать что бы создалась БД
иначе будет выдавать ошибку подключения к БД.

Если вы видите ошибку подключения к БД, то просто немного подождите и снова перезагрузите 
страницу сайта

Доступ к сайту по ссылке http://localhost:8000

Доступ к PhpMyAdmin по ссылке http://localhost:8080

Остановка сервисов командой: docker-compose down

# Хранилище данных БД
Данные БД сохраняются в папке db

# Хранилище данных Joomla
Данные Joomla сохраняются в папке joomla
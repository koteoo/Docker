1. Создал свой кастомный образ NGINX, заменил default страницу, путем монтирования директории к контейнеру.
2. Отличие контейнеров и VM,  в том что, VM полная копия OS, более тяжеловесная, так как имитирует полную архитектуру. А контейнер более легковесный, более переносимый и обладает необходимыми зависимостями для запуского приложения.
3. Собрать ядро в контейнере можно, но возможно нет необходимости в этом, так как все созданные контейнеры используют одно, общее ядро хоста.
4. Собранный образ "зупушил" в dockerhub. 
5. Также выполнил задание на половину звездочки))) Все файлы в github, ссылки прикрепил.

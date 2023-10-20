# DE_1.2
DE Задание 1.2 Docker
Создан docker-compose
Подключен volume

Для запуска необходимо выполнить в CMD из папки с docker-compose:
docker compose up -d

Для подключения к работающему контейнеру и запуска интерфейса psql выполнить в CMD: 
docker exec -it docker-postgres-1 psql -U username -d database


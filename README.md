# DE_1.2
DE Задание 1.2 Docker
Для создания образа выполнить в CMD из папки с dockerfile:
docker build -t test_image:latest .
Для запуска контейнера выполнить в CMD:
docker run -d -p 5430:5432 --name test_container test_image:latest

Для подключения к работающему контейнеру и запуска интерфейса psql выполнить в CMD:
docker exec -it test_container psql -U username -d database



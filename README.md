# DE_1.2
DE Задание 1.2 Docker
Для создания образа запустить в CMD:
docker build -t test_image:latest .
Для запуска контейнера запустить в CMD:
docker run -d -p 5430:5432 --name test_container test_image:latest


# Статический веб-сервер Nginx в Docker

## Запуск проекта
1. Собрать образ: `docker build -t nginx-site:latest .`
2. Запустить контейнер: `docker run -d --name nginx-site -p 80:80 nginx-site:latest`

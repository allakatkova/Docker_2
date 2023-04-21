# Склады и товары

## Документация по проекту

Для запуска проекта необходимо:

1. Открыть терминал, перейти в директорию проекта:

2. Создать образ, используя следующую команду:

```bash
docker build . --tag=crud_app
```

3. Для запуска контейнера с приложением выполнить команду:

```bash
docker run -d -p 8000:8000 --name=docker_app crud_app
```

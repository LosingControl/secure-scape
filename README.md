# SecureScape
Задание разрабатывалось командой из 5 человек в рамках 2-х дневного SECON.Хакатона

## Требования к запуску
Инструменты для запуска:
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)

### .env файлы
Для запуска необходимо будет в директориях, которые указаны ниже, создать файлы `.env` по примеру, который лежит в этой же директории `example.env`:
- `src/EduPlatform.Entry/.env`; 
- `src/EduPlatform.TaskService/.env`; 
- `src/EduPlatform.UserService/.env`.

## Запуск с помощью Docker-compose
Для запуска приложения SecureScape необходимо выполнить следующую команду:
```bash
docker-compose up --build
```
Для завершения, необходимо выполнить команду:
```bash
docker-compose down
```

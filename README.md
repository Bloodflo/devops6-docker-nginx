# DevOps Course 2024 - Docker Nginx

## Описание
Развёртывание веб-сервера Nginx в Docker контейнере с портом 54321

## Структура
- deploy.sh - скрипт развёртывания
- nginx/ - файлы для образа (dockerfile, index.html, nginx.conf)
- screenshots/ - скриншоты работы

## Запуск
```bash
chmod +x deploy.sh
sudo ./deploy.sh

## Проверка
curl 127.0.0.1:54321

## Результат
Веб-сервер доступен на порту 54321

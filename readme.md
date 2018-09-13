# Инструкция запуска и работы

Суть этого репозитория в том что бы насадить готовый html шаблон и отправить в продакшен.

## Разработка и деплой

При запуске jekyll у нас есть несколько важных ключей

1. ```--config _name-config.yml``` Запустит jekyll c *кастомным конфигурационным файлом*
2. ```--livereload``` Автоматическая перезагрузка в браузере при изменениях в коде

### Разработка

Конфигурационный файл ```_dev.yml``` нужен для запуска режима разработки. Сам режим запускает при помощи ключа ```--config _dev.yml```

#### Пример команды

```jekyll serve --config _dev.yml --livereload```

### Деплой

## Структура папок

В папкке `index-pagination-pages`  лежат индексные страницы пагинации колекций и категорий





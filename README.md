# Ахмед Саиф

Backend-разработчик. Делаю серверные приложения на Python: REST API, Django/DRF и FastAPI-сервисы, работу с базами данных, контейнеризацию, деплой и CI/CD.

Мне интересны продуктовые backend-системы, где важны понятная архитектура, надежность, тесты, воспроизводимый запуск и аккуратная документация.

## Основной стек

| Направление | Технологии |
| --- | --- |
| Backend | Python, Django, Django REST Framework, FastAPI |
| Базы данных | PostgreSQL, SQLite, MySQL |
| Асинхронные задачи и брокеры | Celery, Redis, Kafka |
| Инфраструктура | Docker, Docker Compose, Nginx, Gunicorn, Linux |
| Качество | Pytest, unittest, GitHub Actions, GitLab CI |
| Инженерная база | REST API, аутентификация, ООП, SOLID, TDD, KISS, DRY |

## Проекты

### Атрибуция конверсий: (Yandex.Direct API, Yandex.Metrika API, WB API, OZON API, Telegram-bot)

Коммерческий backend-проект для связки рекламных кликов с заказами маркетплейса и отправки оффлайн-конверсий в Яндекс Метрику для оптимизации ставок.

- Обработка около 12k событий в час на FastAPI async и PostgreSQL.
- Снижение потерь трекинга за счет `sendBeacon` и `keepalive`.
- Эвристический матчинг кликов и заказов по времени, товару и региону.
- Фоновые задачи через Celery и RabbitMQ.
- Идемпотентный синк заказов с использованием advisory locks в PostgreSQL.

Проект в продакшене, детали под NDA. Архитектуру, ограничения и метрики могу разобрать на собеседовании.


### GPS Tracker Web Service

Публичный сервисный вариант для приема, хранения и отображения координат GPS-трекеров GF22. В проекте есть HTTP-прием данных, сохранение в БД, REST API и карта с визуализацией точек.

Репозиторий: [GpsTracker](https://github.com/A7med373/GpsTracker)

### Barter Platform

MVP-платформа для обмена товарами между пользователями. Есть регистрация и аутентификация, объявления, фильтрация, предложения обмена, PostgreSQL, Docker и Nginx.

Репозиторий: [barter_platform](https://github.com/A7med373/barter_platform)

### Django Tree Menu

Django-приложение с древовидным меню, которое хранится в базе данных и рендерится через template tag. Меню поддерживает активный пункт по URL, несколько меню на одной странице, редактирование через админку и отрисовку за один запрос к БД.

Репозиторий: [UpTrader](https://github.com/A7med373/UpTrader)

### Foodgram

Приложение для рецептов и списка покупок с backend API, контейнеризацией и инфраструктурой для запуска.

Репозиторий: [foodgram-st](https://github.com/A7med373/foodgram-st)

### Mini Tasks API

Небольшой REST API на FastAPI для управления задачами. Есть валидация данных, примеры запросов и тесты.

Репозиторий: [miniAPI_tasks](https://github.com/A7med373/miniAPI_tasks)

## Сейчас фокусируюсь на

- Backend-проектах с production-like окружением.
- Django REST Framework и FastAPI.
- Docker, CI/CD и деплое на Linux-серверы.
- Очередях задач, кешировании и брокерах сообщений: Celery, Redis, Kafka.
- Алгоритмах и структурах данных на Python.

## Контакты

- Email: [a7medsaif2005@gmail.com](mailto:a7medsaif2005@gmail.com)
- Telegram: [@AlasriAhmedSaif](https://telegram.me/AlasriAhmedSaif)
- LinkedIn: [Ahmed Saif Alasri](https://www.linkedin.com/in/ahmed-saif-alasri/)

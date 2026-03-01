# Kittygram — социальная сеть для любителей кошек 🐱

![Kittygram Workflow Status](https://github.com/Port-tf/kittygram/actions/workflows/kittygram_workflow.yml/badge.svg)

## 📋 Описание проекта

Kittygram — это полнофункциональное веб-приложение, социальная сеть для публикации фотографий кошек. Пользователи могут создавать профили своих питомцев, загружать их фотографии, указывать достижения (достижения) и просматривать карточки других котиков.

### Основные возможности:
- Регистрация и авторизация пользователей
- Создание, редактирование и удаление карточек котиков
- Загрузка изображений
- Присвоение питомцам различных достижений
- Просмотр ленты с котиками других пользователей
- Адаптивный дизайн

## 🛠 Стек технологий

### Backend
- Python 3.9
- Django 3.2.3
- Django REST Framework 3.12.4
- PostgreSQL 13.10
- Gunicorn 20.1.0

### Frontend
- Node.js 18
- React 17.0.2
- CSS Modules

### Инфраструктура
- Docker & Docker Compose
- Nginx 1.22.1
- GitHub Actions (CI/CD)
- Certbot (Let's Encrypt)

## 🚀 Развертывание проекта

### Требования
- Установленные Docker и Docker Compose
- Доменное имя, привязанное к серверу
- Открытые порты 80 и 443

### Переменные окружения

Создайте файл .env в корне проекта:

`env
# Django settings
SECRET_KEY=your-secret-key-here
DEBUG=False
ALLOWED_HOSTS=your-domain.com,localhost

# Database settings
POSTGRES_DB=kittygram
POSTGRES_USER=kittygram_user
POSTGRES_PASSWORD=strong_password
DB_HOST=db
DB_PORT=5432


# Автор
Мостынец Никита Витальевич
GitHub: mostyecnikita
Проект выполнен в рамках финального задания Яндекс.Практикума


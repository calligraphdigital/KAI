# JARVIS — Telegram Bot

## Деплой на Railway (5 минут)

### 1. Загрузи файлы на GitHub
- Создай аккаунт на github.com
- Создай новый репозиторий (New repository)
- Загрузи три файла: jarvis_bot.py, requirements.txt, railway.toml

### 2. Задеплой на Railway
- Открой railway.app
- Войди через GitHub
- Нажми "New Project" → "Deploy from GitHub repo"
- Выбери свой репозиторий

### 3. Добавь секреты (Variables)
В Railway → твой проект → Variables → добавь:
```
TELEGRAM_TOKEN = твой_токен_от_BotFather
ANTHROPIC_API_KEY = твой_ключ_от_Anthropic
```

### 4. Deploy
Railway автоматически запустит бота. Готово!

## Команды бота
- `/start` — запуск
- `/memory` — показать что бот помнит о тебе
- `/clearmemory` — очистить память

## Что умеет
- Помнит важные факты о тебе между сессиями
- Сохраняет контекст последних 20 сообщений
- Характер Джарвиса из фильма

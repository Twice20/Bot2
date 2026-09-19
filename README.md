# WerareAi (Aiti 1.8) Telegram WebApp & Bot

## Быстрый запуск на сервере

1. Распакуйте архив:
   unzip werare_ai_bot.zip -d werare_ai
   cd werare_ai

2. Заполните файл .env вашими токенами:
   nano .env

3. Запуск через Docker (самый надежный способ):
   docker compose up -d --build

4. Или запуск напрямую через Python:
   pip install -r requirements.txt
   python server.py

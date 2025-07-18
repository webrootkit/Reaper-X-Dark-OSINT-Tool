# Kyosuke

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)
![Tor](https://img.shields.io/badge/Tor-Enabled-red?logo=tor-project)

**Kyosuke** — мощный инструмент для сбора информации (OSINT) с поддержкой **Tor, даркнета и Telegram**.  
Идеально для **этичного хакинга, пентеста и расследований**.

---

## 📌 Возможности
- Поиск в **даркнет-форумах** (через Tor)
- Проверка **Telegram-аккаунтов** (без API)
- Генератор **фейковых данных** для тестов
- Автосохранение в **JSON**
- Поддержка **прокси и многопоточности**

---

## ⚡ Быстрый старт
1. **Установи зависимости**:
   ```bash
   pip install requests beautifulsoup4 telethon stem pysocks
   python Reaper-X-Dark.py --target "example@mail.com" --darknet

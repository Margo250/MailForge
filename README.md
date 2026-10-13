# MailForge

Настольный почтовый клиент для Windows с локальным хранением, семантическим
поиском и генерацией черновиков ответов с помощью локальной языковой модели.

## Что умеет

**База:**
- Подключение к почте по IMAP/SMTP
- Список писем, чтение, отправка
- Папки и сортировка на правилах
- Поиск по тексту
- Локальное хранение (SQLite, работает без интернета)

**Фишки:**
- Семантический поиск по смыслу (ChromaDB + эмбеддинги)
- Аналитика переписки (метрики и графики)
- Прототип ИИ-ответчика (черновик на основе переписки)

## Стек

Python 3.11+, PyQt6, SQLite, ChromaDB, sentence-transformers, Ollama.

## Статус

В активной разработке. Учебный проект.

## Запуск

```bash
git clone https://github.com/your-username/mailforge.git
cd mailforge
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python main.py

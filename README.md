# GreenLife

Каталог технологий, которые **улучшают жизнь людей и не вредят природе**: свет без дыма, вода без яда, еда без убитой почвы, город без жары бетона.

- **База:** SQLite (`backend/data/greenlife.db`)
- **Бэкенд:** FastAPI
- **Фронтенд:** React + Vite

## Запуск

```bash
cd backend
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8000
```

В другом терминале:

```bash
cd frontend
npm install
npm run dev
```

Откройте http://localhost:5173

API: http://127.0.0.1:8000/docs

## Что внутри

Категории: чистая энергия, вода, еда и почва, город, движение, цикл отходов.

У каждой технологии есть польза людям, бережность к природе, метрики и живой пример. Через страницу «Добавить» запись сразу попадает в базу.

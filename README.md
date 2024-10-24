# AI_Ch_stock_prediction-
# AI Stock Prediction Project

Этот проект посвящен предсказанию котировок акций с использованием моделей машинного обучения и анализа новостных ресурсов.

## Структура проекта

- **`data/`** — Папка с датасетами:
  - `final_data.txt` — Финальные данные, использованные для предсказания котировок.
  - `news_sentiment_dataset.cs.csv` — Датасет с новостями и их разметкой по тональности.

- **`news_analysis/`** — Папка с кодом для анализа новостей:
  - `news_sentiment_analysis.ipynb` — Ноутбук с анализом тональности новостей. Этот код анализирует новостные заголовки, используя BERT, для определения их влияния на котировки.

- **`prediction_model/`** — Папка с кодом модели для предсказания котировок:
  - `prediction_model.ipynb` — Ноутбук с кодом для предсказания изменения котировок акций на основе исторических данных и новостей.

- **`tg_bot/`** — Папка с кодом для Telegram-бота:
  - `tg_bot.ipynb` — Ноутбук с кодом для Telegram-бота, который предоставляет пользователям данные по котировкам акций, анализирует новости и отображает результаты с графиками.

## Как использовать

### 1. Анализ новостей
- Откройте и выполните ноутбук `news_analysis/news_sentiment_analysis.ipynb` для анализа новостей. Этот ноутбук использует модель BERT для анализа тональности новостей, чтобы оценить их влияние на движение котировок.

### 2. Модель предсказания котировок
- Откройте ноутбук `prediction_model/prediction_model.ipynb`, чтобы запустить модель предсказания котировок. Эта модель обучена на исторических данных и результатах анализа новостей и прогнозирует будущие изменения цен на акции.

### 3. Telegram-бот
- Откройте ноутбук `tg_bot/tg_bot.ipynb`, чтобы настроить и запустить Telegram-бота. Бот предоставляет информацию о текущих котировках акций, прогнозирует будущие цены, анализирует новости и предоставляет графики в реальном времени.

## Streamlit приложение

Попробуйте наше интерактивное приложение на [Streamlit](http://5.253.62.232:8501/), которое предоставляет прогнозы котировок акций на основе новостей и исторических данных.

## Датасеты
- **news_sentiment_dataset.cs.csv** — Датасет с новостями и их тональностью, который используется для анализа влияния новостей на котировки.
- **final_data.txt** — Финальный датасет с историческими данными о котировках, использованный для обучения и тестирования модели.

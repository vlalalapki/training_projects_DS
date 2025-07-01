# 💡 Учебные и тестовые проекты по Data Science

![Python](https://img.shields.io/badge/Python-2e2e2e?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logoColor=black)
![Time Series](https://img.shields.io/badge/Time%20Series-6A5ACD?style=for-the-badge)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-505050?style=for-the-badge&logo=huggingface)

Этот репозиторий включает проекты, выполненные в рамках курса **«Специалист по Data Science»** от [Яндекс Практикума](https://practicum.yandex.ru/data-scientist/) в 2023 году и несколько проектов, выполненных в рамках тестовых заданий и самостоятельной практики. <br>
Проекты охватывают различные решения прикладных бизнес-задач — от исследования и визуализации данных до построения и оценки ML-моделей.

---

## Полученные навыки и изученные инструменты

- **Обработка и анализ данных**: Pandas, NumPy, визуализация через `Matplotlib`, `Seaborn`, `Plotly`.
- **Работа с SQL**: написание сложных запросов, объединения, агрегирование, подготовка данных для анализа.
- **Теория вероятностей и основы статистики**: распределения данных, доверительные интервалы.
- **Машинное обучение**: классификация, регрессия, кластеризация, метрики (`Scikit-learn`, `CatBoost`, `LightGBM`, `XGBoost`).
- **Оценка моделей**: кросс-валидация, метрики, подбор гиперпараметров.
- **Анализ временных рядов**: прогнозирование спроса, ресемплирование, скользящее среднее.
- **Проведение A/B-тестов и анализ гипотез**: статистические тесты, проверка гипотез, выбор критериев, p-value.
- **Работа с текстами NLP**: TF-IDF, токенизация, дообучение языковых моделей (`PyTorch`, `Transformers`).
- **Работа с изображениями CV**: сверточные нейросети (CNN), классификация, сегментация, предобученные модели (`scikit-image`, `PyTorch`, `Torchvision`).

--- 
 
## 📁 Проекты в репозитории

| 🔢 | Проект | Тематика | Навыки и технологии | Описание |
|----|--------|:--------:|:-------------------:|-------------|
| 1️⃣ | **Продажи видеоигр**<br/>[games_sales](./games_sales) | Исследовательский анализ | EDA, Pandas, NumPy, Matplotlib, Seaborn, SciPy | Исследование данных о продажах видеоигр с целью выявления закономерностей. Задача фокусируется на проведении разведывательного анализа данных (EDA), выявления трендов и проверки статистических гипотез. |
| 2️⃣ | **Оптимизация золотодобычи**<br/>[more_gold](./more_gold) | Регрессия | EDA, Pandas, NumPy, Scikit-learn | Построение модели машинного обучения, способной предсказывать эффективность обогащения сырья и выхода золота на различных стадиях производственного цикла. |
| 3️⃣ | **Оценка стоимости автомобилей**<br/>[car_price](./car_price) | Регрессия | EDA, CatBoost, LightGBM, Scikit-learn | Построение модели оценки стоимости автомобиля на основе его параметров. |
| 4️⃣ |**Прогноз заказов такси**<br/>[time_series_taxi](./time_series_taxi) | Временные ряды |  EDA, statsmodels, CatBoost, Scikit-learn | Построение модели прогнозирования спроса на такси в будущем временном промежутке. |
| 5️⃣ | **Анализ оттока клиентов**<br/>[final_telecom](./final_telecom) | Классификация | EDA, CatBoost, Scikit-learn, ROC-AUC | Построение модели предсказывающую вероятность ухода клиента от телеком-оператора на основе его исторических данных и характеристик использования услуг. |
| 6️⃣ | **Извлечение фрагментов текста**<br/>[text_extraction](./text_extraction)| NLP, QA | EDA, PyTorch, Transformers | Построение модели машинного обучения, которая будет находить и выделять в документах текстовые части, по заданному пункту анкеты и контексту самого документа. |
| 7️⃣ | **Определение сгенерированных изображений**<br/>[generated_or_not](./generated_or_not) | CV, Классификация | EDA, scikit-image, PyTorch, Torchvision | Построение модели машинного обучения для автоматического определения, являются ли изображения сгенерированными или настоящими фотографиями. |


---

> Каждый проект снабжен собственным README с описанием задачи, этапов решения и выводами.

---

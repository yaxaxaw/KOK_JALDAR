# K .JALDAR — E-commerce AI Text-to-SQL Agent

**Final Project | Databases Course 2025 | Lecturer: Nargiza Zhumalieva | 60% of final grade**

<img src="https://i.imgflip.com/8x8y5j.jpg" width="300" align="right"/>

## Команда — Чемпионы с первого дня
| Роль           | Имя       | GitHub |
|----------------|-----------|------|
| DB Architect   | Канат     | —    |
| DB Analyst     | Бексултан | —    |
| SQL Developer  | Азимбай   | —    |
| AI Engineer    | Эмирхан   | —    |

## Датасет — ЛУЧШИЙ ВЫБОР С ПЕРВОГО ДНЯ
**[Online Retail Transaction Data](https://www.kaggle.com/datasets/thedevastator/online-retail-transaction-data)**  
541 909 реальных транзакций интернет-магазина подарков (UK, 2010–2011)  
Из 1 CSV → 6+ нормализованных таблиц → идеально под все требования

## 4 бизнес-проблемы (Problem Statement) — ГОТОВО
1. Топ-10 продуктов, приносящих 80% прибыли (Pareto 80/20)  
2. RFM-анализ клиентов: кто VIP, кто churn, кого возвращать  
3. Сезонность и география продаж — где и когда запускать рекламу  
4. Расширение ER-модели: добавление `Suppliers` + `Shipments` для прогнозирования дефицита

## Структура проекта
├── ER_diagram/          # ER-диаграмма (уже готова)
├── sql/                 # create_tables.sql, indexes.sql, views.sql
├── data/                # online_retail.csv (541k строк)
├── notebook/            # Online_Retail_Text_to_SQL_Agent.ipynb
├── docs/                # Technical Report + слайды (Snoop Dogg approved)
├── screenshots/         # гифки работы агента
├── requirements.txt
└── .env.example
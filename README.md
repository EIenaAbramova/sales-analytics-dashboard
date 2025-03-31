# 📊 Дашборд для анализа продаж

## 📝 Описание  
Данный дашборд в Power BI предназначен для анализа ключевых показателей продаж за период с 01.01.2022 по 30.04.2022.  
Визуализация помогает оценивать эффективность, рентабельность и структуру выручки по различным направлениям.

Функциональность дашборда включает:
- Отображение выручки, прибыли, количества активных клиентов (АКБ), среднего чека и затрат на логистику;
- Расчёт рентабельности за выбранный период;
- Динамику ключевых показателей по месяцам и кварталам;
- Сегментацию покупателей (Consumer, Corporate, Home Office и др.);
- Распределение продаж по регионам (на карте);
- Анализ по номенклатуре с отображением прироста;
- ABC-анализ клиентов;
- Выявление заказов с отрицательной прибылью и проблемных менеджеров.

## 📂 Состав проекта  
- `sales-dashboard.pbix` – Файл дашборда Power BI  
- `README.md` – Описание проекта  
- `data/` – (опционально) Исходные данные или примеры  

## 📊 Ключевые показатели:
- Общая выручка  
- Общая прибыль  
- Количество АКБ  
- Средний чек  
- Рентабельность (%)  
- Затраты на логистику  
- Динамика KPI по времени  
- Сегментирование клиентов  
- ABC-анализ  
- Отрицательные заказы по менеджерам  

## 🧮 Логика расчёта метрик / Metric Calculation Logic

**1. Рентабельность (%)**  
Рентабельность = (Прибыль / Выручка) * 100

**2. Средний чек**  
Средний чек = Выручка / Кол-во заказов

**3. ABC-анализ**  
Группировка клиентов по объёму выручки:
- A — 70% выручки
- B — 20%
- C — 10%

**4. Сегментация клиентов**  
Доли клиентов по категориям (визуализировано в горизонтальной гистограмме)

**5. Выявление заказов с убытками**  
Фильтрация заказов с отрицательной прибылью, группировка по менеджерам.

## 🖥️ Как использовать дашборд?  
1. Скачайте файл `sales-dashboard.pbix`  
2. Откройте его в Power BI Desktop  
3. Обновите или загрузите свои данные через Power Query  
4. Используйте фильтры для анализа интересующих показателей

## 🚀 Используемые технологии  
- Power BI (визуализация, DAX, Power Query)  
- Excel (обработка исходных данных)  
- SQL и Python (для подготовки данных — опционально)

## 🎨 Примеры визуализаций  
Вот так выглядит дашборд:  
![Image](https://github.com/user-attachments/assets/c7c913d0-1b28-4463-a70d-b4f5a4fbe844)

## 📜 Лицензия  
Проект распространяется под лицензией MIT — свободное использование с указанием авторства.  
См. файл `LICENSE`.


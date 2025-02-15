# **Анализ данных E-commerce с визуализацией в Power BI**  

## **Описание проекта**  
Этот проект посвящён **анализу данных продаж и визуализации** с помощью **Power BI**.  
Мы исследуем **продажи, клиентов и финансовые показатели**, чтобы получить представления о рынке и конкретные бизнес-выводы.  

---

## **Данные**  
Используется датасет **`E-commerce_data_cleaned.csv`**, содержащий информацию о:  
- **Покупках** 
- **Клиентах** 
- **Магазинах** 
- **Времени транзакций** 
- **Товарах**

Более подробную информацию о датасете можно найти в notebook.ipynb

---

## Структура проекта

```
E-commerce-Analysis_PowerBI/
├── data/                       # Данные для анализа
├── notebook.ipynb              # Jupyter-ноутбук с анализом данных
├── requirements.txt            # Зависимости проекта
└── README.md                   # Этот файл
```

## **Визуализация в Power BI**  
...

---

## **Основные выводы**  

📌 **1. Продажи стабильны, но сезонности нет**  
- График продаж по месяцам не показывает **чёткой сезонности**  
- Продажи **равномерно распределены**  

📌 **2. Средний чек стабилен, но у некоторых клиентов выше**  
- В среднем клиенты тратят **105,4 единиц за покупку**  

📌 **4. Географический анализ показал, что продажи сосредоточены в DHAKA**  
- Визуализация на карте показала, где больше всего клиентов  
- Можно **расширить маркетинг в менее активных регионах**  

📌 **5. Кластеризация клиентов не выявила чётких групп**  
- Анализ с KMeans и DBSCAN показал, что клиенты **распределены плавно**, без явных сегментов  

---

---

## **Инструменты**  
- **Power BI** – Визуализация данных  
- **Pandas, Plotly, Matplotlib** – Анализ данных  
- **Scikit-learn** - для кластеризации

---

**© 2025 Проект по анализу и визуализации данных при помощи PowerBI.**


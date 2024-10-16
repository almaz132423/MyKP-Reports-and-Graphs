# Создание Отчетов и Графиков

## Описание

Проект для работы с базой данных SQLite в приложении WPF, предназначенный для:

- Визуализации данных в виде столбчатого графика с использованием **LiveCharts.Wpf**.
- Экспорта данных в **Excel** и **Word**.

## Функциональность

1. **Подсчет средних цен**: Подсчет средних цен товаров для каждой категории на основе данных из базы данных.
2. **Графическая визуализация**: Отображение столбчатого графика в WPF-приложении, где X-ось — это категории, а Y-ось — средняя цена.
3. **Генерация отчета**: Текстовый отчет, сохраняемый на рабочем столе.
4. **Экспорт в Excel и Word**: Экспорт средних цен в файлы Excel и Word.

## Пример текстового отчета

# Отчёт о средних ценах по категориям

| Категория            | Средняя цена (руб.) |
|----------------------|---------------------|
| Электроника          | 39,999.99           |
| Книги                | 499.99              |
| Одежда               | 799.99              |
| Бытовая техника      | 2,999.99            |
| Игрушки              | 1,499.99            |
| Красота и уход       | 299.99              |
| Спортивный инвентарь | 15,999.99           |
| Автотовары           | 1,199.99            |
| Канцтовары           | 49.99               |
| Продукты питания     | (Примерная цена)    |

---

**Дата создания отчёта**: 16.10.2024

## Пример Графика
График отображает средние цены по категориям:

**Ось X** — категории товаров.
**Ось Y** — средняя цена товаров в рублях.

![image](https://github.com/user-attachments/assets/baf98ecf-2cd0-41b9-ae86-af72db605465)


### Клонирование репозитория:

```bash
git clone https://github.com/your_username/CategoryPriceReports.git
cd CategoryPriceReports

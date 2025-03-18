# Расчет сезонности в данных о чеках ресторанов

Этот репозиторий содержит Jupyter Notebook (`test_task.ipynb`), который выполняет анализ данных о количестве чеков в ресторанах за период с 2023-01-01 по 2024-12-29 и вычисляет коэффициенты сезонности для каждого ресторана по номерам недель (1-52).

## Описание данных

Исходные данные находятся в файле `rest_checks.csv` и содержат следующую информацию:

*   `rest_ncode`: Номер ресторана (идентификатор).
*   `check_dt`: Дата пробития чека.
*   `checks_qty`: Суммарное количество чеков за указанную дату в указанном ресторане.
*   `regionrf_name`: Регион расположения ресторана.
*   `restformat_name`: Формат ресторана.

## Запуск

Установите библиотеки, если они еще не установлены:

```bash
pip install pandas numpy matplotlib seaborn prophet
```

Затем откройте и запустите ноутбук `test_task.ipynb`

## Файлы

*   `rest_checks.csv`: Исходные данные.
*   `test_task.ipynb`: Jupyter Notebook с кодом.
*   `rest_checks.xlsb`: Исходные данные в формате .xlsb.

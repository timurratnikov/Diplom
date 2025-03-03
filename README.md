# HISTORY

Объединил датасеты по месяцам с один + почистил. Файл preprocess.ipynb | Очищенный датасет файл data/cleared_dataset.csv - gitignored 
После объдинения
Убрал у колонок ДатаДоставки, ДатаЗаказаНаСайте суффикс 0:00
Убрад записи где у колонок ДатаЗаказаНаСайте, ДатаДоставки некорректные значения (типо nan, 2104-10-10)

4.326 млн записей получилось в cleared_dataset.csv

---------

Сделал файлы statistics/sold_data.csv|placed_data.csv|reedemability.csv через ноутбук summary_table.ipynb

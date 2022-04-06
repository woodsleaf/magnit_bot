# Скрипт магазина Magnit

Формирует по выбранному городу csv файл с информацией о товарах со скидкой на текущий день.

### Prepare

<pre>
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
</pre>

### Use

python3 main.py

### Example ready csv file

<pre>
Санкт-Петербург_06_04_2022_02_57.csv
Продукт,Старая цена,Новая цена,Процент скидки,Время акции
"Суп СЕМЕЙНЫЕ СЕКРЕТЫ, Грибной/Гороховый, 60г",−19%,23.00,16.99,с 06 апреля до 12 апреля
"Корм для собак ФРИСКИС Говядина в подливе, 85г",−11%,19.10,16.99,с 06 апреля до 12 апреля
"Корм для собак ФРИСКИС Ягненок в подливе, 85г",−11%,19.10,16.99,с 06 апреля до 12 апреля
...
</pre>

### Источник

[pythontoday/magnit_bot](https://github.com/pythontoday/magnit_bot)
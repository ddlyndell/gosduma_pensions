# Определение пенсионеров среди депутатов Госдумы

Парсер собирает информацию о депутатах с сайта Госдумы: имя, ссылку на профиль и день рождения. Записывает все в CSV-файл. 

Пол расставляется вручную, возраст вычислен в [Google Spreadsheets](https://docs.google.com/spreadsheets/d/1N4LZCI75PA9WpXfE9Jq9FatcMj3szu8LF4ATBNk-QL4/edit?usp=sharing) функцией DATEDIF от сегодняшнего дня (25 октября 2018), пенсионеры определены исходя из возраста 55 лет для женщин и 60 лет для мужчин. 

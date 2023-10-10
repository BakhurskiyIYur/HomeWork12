# Домашнее задание №12 (Тема "Секционирование")

<br>__*Разворачиваю виртуальную машину, на ней устанавливаю PostgreSQL 15 версии. Далее на виртуальную машину записываю резервную копию демонстрационной базы данных Demo в подготовленную заранее директорию /home/postgres/backup.*__
> <img src="pic/0.JPG" align="center" />

<br>__*Далее выполняю полученный скрипт:*__
> <img src="pic/1.JPG" align="center" />

<br>__*Убеждаюсь, что демонстрационная база данных Demo создалась:*__
> <img src="pic/2.JPG" align="center" />

<br>__*В базе данных уже присутствуют таблицы с данными:*__
> <img src="pic/3.JPG" align="center" />

<br>__*Просмотрев все таблицы, их структуру, решаю секционировать таблицу bookings по диапазону дат (т.е. по полю book_date):*__
> <img src="pic/13.JPG" align="center" />

<br>__*Новую таблицу с именем bookings_part создаю следующим образом:*__
> <img src="pic/4.JPG" align="center" />

<br>__*qqq*__
> <img src="pic/5.JPG" align="center" />

<br>__*qqq*__
> <img src="pic/6.JPG" align="center" />

<br>__*qqq*__
> <img src="pic/7.JPG" align="center" />

<br>__*qqq*__
> <img src="pic/8.JPG" align="center" />

<br>__*qqq*__
> <img src="pic/9.JPG" align="center" />

<br>__*qqq*__
> <img src="pic/10.JPG" align="center" />

<br>__*qqq*__
> <img src="pic/11.JPG" align="center" />





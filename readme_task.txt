Тестовое задание

1.	Разработать web-страницу с элементами
1.1.	Количество горизонтальный ползунок на значениях от 1 до 10.  Дефолтное значение 5.
1.2.	Значения       Цвет (отрезке значений)
1-3                     зеленый
4-6                     желтый
7-8                     красный
9-10                  черный (на всем значении от 1 до 10)
1.3.	Поле ввода   е-mail с валидацией
1.4.	Поле ввода  ФИО (только латинские буквы)
1.5.	Кнопка Отправить. При нажатии упаковываем значения в json и вызываем метод SaveData сервиса из п 2.
1.6.	Отобразить на странице результат работы метода.

2.	Разработать сервис с методом SaveData. Валидирует полученные данные и сохраняет их в БД с помощью вызова процедуры sp_SaveData. Если количество четное, процедура возвращает 0, если нечетное, возвращает 1. Результат отправляется сервисом в виде result=True/False.
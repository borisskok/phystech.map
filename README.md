# phystech.map

Это проект Бориса, Кристины и Сони. Мы делаем телеграм-бота phystech.map, который по начальной и конечной точке построит маршрут внутри Физтеха. 

для запуска бота со своего компьютера необходимо:

1) необходима установка библиотеки telebot для Python и g++ с поддержкой не ниже c++11
> pip3 install pytelegrambotapi
2) склонировать всю папку DONE/
3) в папке DONE запустить бота 
> python3 bot.py
4) пользоваться)))
  
Борис написал бота)
  
Кристина написала алгоритма поиска пути в графе:
>
>Моя часть работы заключается в написании алгоритма Дейкстры, применение его на практике и связь частей кода между собой.
>
>Part_from_Kris.py вызывается из программы Сони(вся информация по поводу работы её программ на её ветке).
>Что делает программа:
>- считывает данные из файла `input.txt`
>- по этим данным строит матрицу в подходящем виде
>- с помощью алгоритма Дейкстры ищет оптимальный маршрут от start до end
>- выводит полученный путь в файл `output_from_Kris.txt`
  

Соня написала связь входного файла Бориса и выходного файла с маршрутом, обращаясь по ходу построения маршрута к Кристининой программе
  
Дисклеймер: это тестовая версия базы данных DataBase, неполная и немного не соответствующая действительности))) (мы это исправим чуть позже)
  
Hope you'll enjoy this

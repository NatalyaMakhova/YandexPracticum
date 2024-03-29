# Анализ рынка недвижимости - продажа квартир в Санкт-Петербурге и соседних населённых пунктах.
## Задача
Используя данные сервиса Яндекс.Недвижимость необходимо выявить основные параметры и факторы, влияющие на рыночную цену квартиры.
## Используемые библиотеки python
- Pandas
- Matplotlib
## Общий вывод
По данным сервиса Яндекc Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Оснавную долю объявлений о продаже занимают квартиры:
 - общей площадью от 40 до 70 кв.м.,
 - высотой потолков от 2.60 до 2.70 метров,
 - имеющие 1,2 комнаты, реже 3
 - стоимостью от 3,5 до 7 млн.руб.
   
Исследование показало что цена квартиры зависит от удаленности от центра, общей площади, количества комнат и этажа на котором находится квартира. Также на цены повлияла и дата размещения объявления. За три года стабильно осенью наблюдалось повышение цен и спад к декабрю и январю, сильное повышение цен замечено в мае 2018, возможно это связано с определенными событиями. Проанализировав центр Санкт-Петербурга можно сделать вывод, что цена на недвижимость резко меняется. Наблюдается максимальный рост цен в радиусе 1км от центра.

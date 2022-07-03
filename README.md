# diplom_version3

Общее:
Данный проект является приложением к дипломной работе по теме: Исследование методов 
машинного обучения в задаче предсказания результатов матчей на профессиональной 
сцене в Counter-Strike: Global Offensive

Дипломная работа посвящена сравнению методов машинного обучения в задаче бинарной классификации на примере матчей в кс:го.

Сбор данных:
За сбор и первичную обработку данных отвечает весть проект, кроме папки research.
В папке parsing все, что отвечает за парсинг данных с сайта hltv.org.
В папке preprocessing все, что отвечает за преобразования мачей из json файлов в csv таблицы, для дальнейшего обучения на них моделей.
Все запускается из файла main.py.

Сравнение методов:
За сравнения методов отвечает папка reseach. В ней находятся данные и 3 папки, каждая из которых посвящена своей таблице, полученной из данных.
Подробнее про сами используемые методы и весь диплом можно прочитать в самой дипломной работе.

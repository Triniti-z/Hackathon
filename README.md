Исполнитель "Чертженик"
=============================
#####Данный проект был реализован в рамках Хакатона 25.11.2017

###Описание задачи и базовые констукции принятые автором данного исполнителя(взято с просотров ваших этих интернетов)

Исполнитель Чертежник предназначен для построения рисунков на координатной плоскости.
При задании точек этой координатной плоскости, в отличие от того, как это принято в математике, координаты х и у разделяются запятой.

Чертежник имеет перо, которое можно поднимать, опускать и перемещать. При перемещении опущенного пера за ним остается след — отрезок от предыдущего положения пера до нового. При перемещении поднятого пера никакого следа на плоскости не остается. В начальном положении перо Чертежника всегда поднято и находится в точке (0, 0).
По команде подними перо Чертежник поднимает перо. Если перо уже было поднято, Чертежник игнорирует эту команду: он не меняет положение пера и не сообщает об отказе. Иначе говоря, каким бы ни было положение пера до команды подними перо, после этой команды оно будет поднятым.
Точно так же, независимо от первоначального положения, после выполнения команды опусти перо оно оказывается опущенным, то есть готовым к рисованию.
Рисунки Чертежник выполняет с помощью команд переведи в точку и сдвинь на вектор. 

По команде переведи в точку (а, b) Чертежник сдвигается в точку с координатами (а, &). На рис. 3.2 показаны результаты выполнения команды переведи в точку (2, 3) при различных положениях пера до этой команды. Видно, что независимо от предыдущего положения перо оказывается в точке (2, 3), но длина и направление отрезка, который при этом чертится, могут быть различны. Команду переведи в точку называют командой абсолютного смещения.

Назовите координаты точек, в которых находился Чертежник до выполнения команды переведи в точку (2, 3).
В каком случае в результате выполнения команды переведи в точку (2, 3) из различных показанных на рис. 3.2 начальных положений не будет прочерчен ни один отрезок?
Пусть перо Чертежника находится в точке (х, у). По команде сдвинь на вектор (а, b) Чертежник отсчитывает а единиц вправо вдоль горизонтальной оси (оси абсцисс), b единиц вверх вдоль вертикальной оси (оси ординат) и сдвигает перо в точку с координатами (х + а; у + b). Таким образом, координаты, указанные в команде, отсчитываются не от начала координат, а относительно текущего положения пера Чертежника. Поэтому команду сдвинь на вектор называют командой относительного смещения.  


![картинка для пивлечения внимания](https://arhivurokov.ru/kopilka/uploads/user_file_53a0573bdfe39/img_user_file_53a0573bdfe39_1.jpg)

Коментарии в коде почти отсутсвуют они и не нужны - всё и так понятно благодаря грамотным именованию переменных.



Ссылка на изображении ведёт на ютуб для видеопрезентации
[![картинка для пивлечения внимания](https://i.ytimg.com/vi/8M2FkraYLOY/maxresdefault.jpg)](https://youtu.be/JVxqLsxDwgU)


>   Данный проект реализован в веб версии с использованием языка JavaScript (мультипарадигменный язык программирования)
 Также для верстки страницы использован HTML+CSS


Установка 
------------

Удобнее всего будет скачать архивом с данного репозитория и распаковать.

Инструкции по установке:

    Распакуйте архив.
    Найдите файл main.html.
    Запустите его. 
    
### Список файлов с описанием их функций

Проект по факту состоит из пары файлов разбросаных по папках. 


```php
Название файла        | Содержание файла
----------------------|----------------------
index.html            | Подготовленный файл для работы и вашего удобства
js                    | Папка со скриптами
styles                | Папка со стилями
README.md             | Файл описание который вы сейчас читаете
----------------------|-----------------------
```



Требования
------------
Стандартные требования к Браузеру.
Ниже они более подробно описаны для вашего удобства

        Операционные системы
            Windows 7
            Windows 8
            Windows 8.1
            Windows 10
        Рекомендуемая системная конфигурация
            Процессор Pentium 4 или более новый, поддерживаюший SSE2
            512 МБ RAM/
            2 ГБ RAM для 64-битной сборки
            200 МБ дискового пространства
        Mac
        Операционные системы
            Mac OS X 10.9
            Mac OS X 10.10
            Mac OS X 10.11
            Mac OS X 10.12
            Mac OS X 10.13
        
        Рекомендуемая системная конфигурация
        
            Компьютер Макинтош с процессором Intel x86
            512 МБ RAM
            200 МБ дискового пространства
        
        Linux
        
        Обратите внимание, что дистрибутивы Linux могут включать в них сборки Firefox, требования которых будут отличаться от приведённых ниже.
        Firefox не будет работать без следующих библиотек или пакетов:
        
            GTK+ 3.4 или выше
            GLib 2.22 или выше
            Pango 1.14 или выше
            X.Org 1.0 или выше (рекомендуется 1.7 или выше)
            libstdc++ 4.6.1 или выше
        
        Для оптимальной работы мы рекомендуем установить следующие библиотеки или пакеты:
        
            NetworkManager 0.7 или выше
            DBus 1.0 или выше
            GNOME 2.16 или выше
            PulseAudio
        
        iOS
        Операционные системы
        
            iOS 10.3 или более поздняя версия
        
        Android
        Операционные системы
        
            Android 4.1 или более поздняя версия
            50 Мб внутренней памяти
            384МБ оперативной памяти
            Дисплей с разрешением не менее 320x240 пикселей




Описание и основные функции реализвоанного проекта
------------

В данном проекте ввод данных для отрисовки упрощен - для этого вам понадобиться только мышка.
Первая команда  к которой вам нужно обратиться это "Опустить Перо".
Далее выбрать координаты к с котором начнется рисование нашего элемента.
Далее выбираем необходимую тракеторию прохождения линии сквозь готовые точки.


![screenshot of sample](http://imagehost.spark-media.ru/i2/60C1D591-F390-CD57-D106-E0F3D53058DB.jpg)



      
        Название кнопки | Содержание столбца
        ----------------|-----------------------------------------------------------------------------------------------------------------------------------------------
        
        -----------------------------------------------------------------------------------------------------------------------------------------------------------------
  



Оставляйте пожелания и исправления в ветке коментирования кода.

Написал логику, ридми файл - [linkedin ](https://www.linkedin.com/in/сергей-обухов-703426140/).
Основная реализация  [linkedin ](https://www.linkedin.com/in/kristrash/).
Внешний вид и стили  [linkedin ](mailto:o.g.makarova2013@gmail.com ).
 

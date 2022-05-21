# LinuxTerminal

1) Посмотреть где я `-pwd`
2) Создать папку `-mkdir Test`
3) Зайти в папку `-cd Test`
4) Создать 3 папки `- mkdir -p First Second Third`
5) Зайти в любоую папку `-cd First`
6) Создать 5 файлов (3 txt, 2 json) `-touch 1.txt 2.txt 3.txt one.json two.json`
7) Создать 3 папки `-mkdir -p under_one under_two under_three`
8) Вывести список содержимого папки `-ls`
9) Открыть любой txt файл `-nano 1.txt`
10) Написать любой текст 
11) Сохранить и выйти `Ctrl+O > Ctrl>X'
12) Выйти из папки на уровень выше `-cd ..`
13) переместить любые 2 файла, которые вы создали, в любую другую папку. `-mv 1.txt 2.txt ~/Documents/Test/Second/`
14) скопировать любые 2 файла, которые вы создали, в любую другую папку. `- cp one.json two.json ~/Documents/Test/Third/`
15) Найти файл по имени -find . -name two.json
16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает. `-tail -f 1.txt | grep -i hello`
17) вывести несколько первых строк из текстового файла `- head -n+2 1.txt`
18) вывести несколько последних строк из текстового файла `- tail -n+2 1.txt`
19) просмотреть содержимое длинного файла (команда less) изучите как она работает. `-less -s 1.txt`
20) вывести дату и время `-date`
***

<h1> Задание 2.1 </h1>
1) `curl "http://162.55.220.72:5005/terminal-hw-request"`
2) `curl "http://162.55.220.72:5005/get_method?name=Helga&age=21"`

<h1> Задание 2.2. </h1>

- #! /bin/bash 
- #Перемещаюсь в папку Test, тк скрипт у меня вложен в доп.папку Test'a
> `cd ..`

- #Создаю три папки
>`mkdir -p First Second Third`

- #Перемещаюсь в первую папку
>`cd First`

- #Создаю 5 файлов. 3 -txt , 2-json 
>`touch 1.txt 2.txt 3.txt one.json two.json`

- #Создаю 2 папки
>`mkdir -p under_one under_two under_three`

- #Просматриваю содержимое папки
>`ls -al`

- #Перемещаю 2 файла в другую директорию
>`mv 1.txt 2.txt ~/Documents/Test/Second/`

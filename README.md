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
11) Сохранить и выйти `Ctrl+O > Ctrl+X`
12) Выйти из папки на уровень выше `-cd ..`
13) Переместить любые 2 файла, которые вы создали, в любую другую папку `-mv 1.txt 2.txt ~/Documents/Test/Second/`
14) Скопировать любые 2 файла, которые вы создали, в любую другую папку `- cp one.json two.json ~/Documents/Test/Third/`
15) Найти файл по имени `-find . -name two.json`
16) Просмотреть содержимое в реальном времени `-tail -f 1.txt | grep -i hello`
17) Вывести несколько первых строк из текстового файла `- head -n+2 1.txt`
18) Вывести несколько последних строк из текстового файла `- tail -n+2 1.txt`
19) Просмотреть содержимое длинного файла (команда less) изучите как она работает `-less -s 1.txt`
20) Вывести дату и время `-date "%D-%T"`
***

<h1> Задание 2.1 </h1>

1. curl "http://162.55.220.72:5005/terminal-hw-request"
>  `% Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   283  100   283    0     0   1951      0 --:--:-- --:--:-- --:--:--  1965{
  "Intro": "Hello!! This is your the first response from server",
  "Tasks": {
    "Task_1": "Send the next URL in terminal: http://162.55.220.72:5005/get_method?name=(set_your_String)&age=(set_your_number)",
    "result": [
      "Your_String",
      "Your_number"
    ]
  }
}`
2. curl "http://162.55.220.72:5005/get_method?name=Helga&age=21"
> `% Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    23  100    23    0     0    188      0 --:--:-- --:--:-- --:--:--   190[
  "Helga",
  "21"
]`

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

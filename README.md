# LR6

Лабораторная работа №6

1. Аккаунт на гитхабе уже существовал
2. Сделан Форк исходного репозитория\
![Форк исходного репозитория](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Форк_исходного_репозитория.png)
3. Клонирован исходный репозиторий\
![Клонирование репо](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Клонирование_репо.png)
4. Добавлен файл через Гитхаб и подтянуты изменения\
![Создание файла](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Создание_файла.png)\
![Подтягивание изменений](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Подтягивание_изменений.png)
5. Получена история изменений для каждой ветки\
![Получить информацию по веткам](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Получить_информацию_по_веткам.png)
6. Выполнен мердж в ветку master, разрешив конфликт.\
![Мердж](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Мердж.png)\
![Резолв конфликта](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Резолв_конфликта.png)
7. Удалена побочная ветка локально и удаленно\
![Удаление ветки](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Удаление_ветки.png)\
8. Создан новый файл и заполнен, при этом создавая коммиты\
![Добавление нового файла](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Добавление_нового_файла.png)\
![Изменение нового файла](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Изменение_нового_файла.png)
9. Сделан hard-reset коммита.\
![Получение хэша и резет коммитов](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Получение_хэша_и_резет_коммитов.png)
10. Создана ветка для отчета\
![Создание новой ветки для отчета](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Создание_новой_ветки_для_отчета.png)
11. Получена история изменений в сокращенном виде\
![Получение истории в сокращенном виде](https://github.com/VityaRa/LR6/raw/report_lobanov/screens/Получение_истории_в_сокращенном_виде.png)
12. Получена история введенных команд\

    500 git clone git@github.com:VityaRa/LR6.git\
    501 cd ./LR6\
    502 ls\
    503 git branch -a\
    504 git log\
    505 git pull origin master\
    506 ls\
    507 git log\
    508 git checkout branch1\
    509 git log\
    510 git checkout master\
    511 git merge branch1\
    512 ls\
    513 cat mergefile.txt\
    514 nano mergefile.txt\
    515 git merge branch1\
    516 git status\
    517 git add .\
    518 git restore --staged .\
    519 git add mergefile.txt\
    520 git status\
    521 git commit -m "feat: resolve merge conflict"\
    522 git branch -a\
    523 git branch -d branch1\
    524 git branch -a\
    525 git push git@github.com:VityaRa/LR6.git branch1 -d\
    526 clear\
    527 touch file_for_hard_reset.txt\
    528 ls\
    529 git add file_for_hard_reset.txt\
    530 git commit -m "feat: add file for HR"\
    531 nano file_for_hard_reset.txt\
    532 git add .\
    533 git restore --staged .\
    534 git add file_for_hard_reset.txt\
    535 git commit -m "feat: fill new file with text"\
    536 git log\
    537 git reset --hard 25e413\
    538 git checkout -b report_lobanov\
    539 nano mergefile.txt\
    540 history\

13. После завершения отчета изменения закомиченны и запушены в репозиторий
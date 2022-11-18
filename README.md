### Лабораторная работа №6

1. Была создана копия репозитория из задания (Create a new fork).
2. С помощью 'git clone' был клонирован личный удаленный репозиторий в специально созданную директорию ('mkdir lab6').
3. С помощью интерфейса GitHub был создан новый файл. Тогда, с помощью 'git pull' были подтянуты изменения в локальный репозиторий.

![Клонирование и подтягивание](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/1.png)

4. Тогда история ветки master ('git log') выглядит так:

![История ветки мастер](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/2.png)

5. Был осуществлен переход на ветку branch1: 'git branch' показывает доступные ветки, 'git checkout <branch1>' осуществляет переход на выбранную ветку.
![Переход на ветку](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/3.png)

Также можно отобразить последние 2 коммита с помощью 'git log -p -2':

![Переход на другую ветку](https://github.com/](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/4.png)

6. Выполнено слияние веток master и branch1 в ветку master с помощью 'git merge branch1', находясь в ветке master

![Слияние веток](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/5.png)

7. Возникает конфликт, который необходимо решить (исправление конфликта на рис. ниже).

![Ошибка](https://github.com/kohosha/finLR6/blob/report/screens/11.jpg)

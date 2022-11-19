### Лабораторная работа №6

## Система контроля версий

  1. Была создана копия репозитория из задания (Create a new fork).

  2. С помощью 'git clone' был клонирован личный удаленный репозиторий в специально созданную директорию ('mkdir lab6').

  3. С помощью интерфейса GitHub был создан новый файл. Тогда, с помощью 'git pull' были подтянуты изменения в локальный репозиторий.

![Клонирование и подтягивание](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/1.png)

  4. Тогда история ветки master ('git log') выглядит так:

![История ветки мастер](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/2.png)

  5. Был осуществлен переход на ветку branch1: 'git branch' показывает доступные ветки, 'git checkout <branch1>' осуществляет переход на выбранную ветку.
  
![Переход на ветку](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/3.png)

Также можно отобразить последние 2 коммита с помощью 'git log -p -2':

![Последние коммиты](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/4.png)

  6. Выполнено слияние веток master и branch1 в ветку master с помощью 'git merge branch1', находясь в ветке master

![Слияние веток](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/5.png)

  7. Возникает конфликт, который необходимо решить (исправление конфликта на рис. ниже).

![Конфликт](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/6.png)

  8. После разрешения конфликта, можно продолжить слияние веток. Были сохранены и подтверждены изменения о их слиянии с помощью commit. Тогда из репозитория (как у себя локально, так и синхронизируя изменения с GitHub командой push.
  
![Конфликт](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/7.png)
  
  9. Были осуществлены некоторые изменения (были созданы файлы с текстом с помощью 'echo'). Эти изменения были подтверждены с помощью commit. Затем была вызвана команда 'git log -3', чтоб показать последние три изменения.
  
![Создание файлов](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/8.png)
  
![История изменений](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/9.png)
  
  10. Для оформления данного отчета была создана ветка labrep с помощью 'git branch labrep'. Загрузить директорию с локального репозитория на GitHub можно с помощью команды 'push'.

  11. Форматированный вид истории операций:
![Форматированный вид истории](https://github.com/paulchamomile/LR6/blob/labrep/screenshots/14.png)
  
  12. Данный отчет был создан в файле README.md (ветка labrep) с markdown-синтаксисом.

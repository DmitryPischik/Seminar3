# Инструкция по работе с GIT

## Что такое GIT
Git наиболее популярная реализация распределёной системы контроля версий. Самая популярная реализация **Git** - [GitHub](https://github.com/)

## Подгатовка репозитория
Для создания репозитория используется команда *git init*. Необходимо в терменале перейти в пустую папку, где в будущем будет репозиторий. Затем в терменеле написать команду *git init*.

## Создание коммитов

### Добавления файла к коммиту
Для добавления файла к будущему коммиту используется команда *git add <название файла>*. 

## Создание коммитов
Для создания коммита необходимо в терминале ввести команду *git commit -m <комменарий>*. Сообщение к коммиту пясать ***ОБЯЗАТЕЛЬНО***

##  Журнал изменений
Для просмотра журнала изменений используется команда *git log*. Для этого в папке-репозитарии необходимо написать *git log*.

## Перемещение между коммитами
Для перемещения на предыдущие коммиты используется команда *checkout*. Для этого необходимо вжурнале изменений, как показано в предыдущей части, найти необходимый коммит и его номер. После чего в терминале с папкой-репозиторием написать команду *git checkout <номер коммита>*. После применения этой команды Вы попадёте в состояние **Detached head**, в котором ни какие изменения фиксироваться не будут.Для возврата в обычное состояние необходимо написать команду *git checkout master*.

## Ветки в GIT

## Слияние веток и разрешение конфликтов

## Удаление веток


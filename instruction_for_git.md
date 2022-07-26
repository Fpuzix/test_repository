# **Инструкция по работе с Git**

## Инициализация репозитория

Чтобы создать новый препозиторий в выбранной папке нужно ввести в терминале команду:

    git init

## Просмотр текущего состояния репозитория

Чтобы посмотреть текеущее состояние репозитория используется команлда

    git status

## Добавление версионности к файлу

Чтобы добавить версионность к файлу необходимо ввести команду и указать наименование файла:

    git add

## Фиксация изменения в репозитории

Чтобы зафиксировать изменения в репозитории необходимо использовать команду:

    git commit -m "comments"

## Просмотр истории изменений

Чтобы просмотреть историю изменений файла необходимо воспользоваться командой:

    git log

## Переключение между коммитами ("сохранениями")

Чтобы переключаться между коммитами необходимо использовать команду, и указать хешкод:

    git checkout 

## Переключение на последнюю актуальную версию

Чтобы быстро переключаться на последнюю актуальную версию необходимо ввести команду:

    git checkout master

## Просмотр разницы между коммитами

Чтобы просмотреть разницу между коммитами необходимо воспользоваться командой, и через запятую ввести два хешкода сравниваемых коммитов:

    git diff хххххх ххххххх
    
# **Ветки в GIT**

## Создание веток

Чтобы создать новую ветку необходимо ввести в терминале команду:

    git btanch name_branch

## Переход между ветками

Чтобы перейти в другую ветку необходимо ввести команду и указать имя ветки без ковычек:

    git checkout name_branch

## Просмотр существующих веток
    
Чтобы просмотреть какие ветки сейчас существуют необходимо ввести команду:

    git branch


## Слияние веток
    
Чтобы осуществить слияние веток, необходимо ввести команду и указать ветку которая будет добавлена:

    git merge

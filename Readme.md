# Инструкция для работы с Git и удаленными репозиториями

## Что такое Git?
Git - это одна из реализаций распределенных систем контроля версий, имеющая как локальные так и удаленные репозитории. Является самой популярной системой контроля версий в мире.
## Подготовка репозитория
Для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создаться репозиторий (появиться скрытая папка .git)

## Создание коммитов

### Git add
Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли изменения в файлах, или их небыло.

### Создание коммитов
Для того, чтобы создать коммит (сохранение) необходимо выполнить команду *git commit*. Выполняется она так
# Инструкция по работе с Git

## Что такое Git?
**Git**- это распределённая система управления версиями.  

 ## Подготовка репозитория
Для создания репозитория, необходимо выполнить команду *git init*, в папке с репозиторияем появится скрытая папка *.git*

## Создание коммитов
1. ### Git status
Для того, чтобы посмотреть состояние репозитория введите команду **git status**. Данная команда покажет были ли изменения в файлах.

2. ### Git add
Используется для добавления файлов в коммит. Выполняется так: Выполняется так: *git add имя файла с расширением*

3. ### Git commit
Используется для создания коммитов. Выполняется так: *git commit -m "Текст обозначающий внесенные изменения"*

4. ### Git log
Вывод на экран всех коммитов с их хэшкодами

5. ### Git checkout 
Переход от одного коммита к другому

6. ### Git diff
Показывает разницу между текущим и закомиченным файлом

![Vse ponyatno?](mem.JPG)

## Работа с удаленным репозиторием 

_Для того, чтобы взаимодействие с Github было успешным, необходимо авторизоваться в VSCode!_

1. ### Git clone <url-адрес репозитория>
Функция используется для клонирования внешнего репозитория на локальный ПК

2. ### Git pull
Получение изменений и слияние с локальной версией

3. ### Git push
Отправляет локальную версию репозитория на внешний

![teper ve ponytno](mem2.JPG)
## Что такое Git?

Git - одна из реализаций распределенных систем контроля версий, имеющая как локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория

***git init*** - для создания репозитория в текущей папке

## Git add

***git add*** *имя_файла*  - для сохранения изменений. 

## Создание коммитов

***git commit -m*** *"Текст сообщения"* - для создания коммита
***git commit -am*** *"Текст сообщения"* - выполняет сразу и *git add* и *git commit -m*

## Создание ветки

***git branch*** *имя_ветки*

или

***git checkout -b*** *имя_ветки* - для создания ветки

## Слияние веток

***git merge*** *имя_ветки* - для добавляет информацию из указанной ветки в текущую

## История изменений

***git log*** - для вывода на экран истории всех коммитов с их хэш-кодами

***git log --oneline*** - для вывода на экран истории всех коммитов без хэш-кодов

## Удаление ветки

***git branch -d*** *имя_ветки* - удаление ветки


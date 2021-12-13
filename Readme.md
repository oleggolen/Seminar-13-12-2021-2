# Инструкция по работе с Git и удалёнными репозиториями


## Создание локального репозитория
Создать локальный репозиторий можно с помощью команды *git init*. Для этого надо применить эту команду в той папке, где в будущем будет репозиторий.

## Добавление файлов в репозиторий
Версионность к файлу добавляется с помощью команды *git add*. Команда применяется следующим образом *git add <название файла>*

## Создание коммита
Для того, чтобы создать новый коммит необходимо использовать команду *git commit*. Применяется она следующим образом: *git commit -m "<сообщение к коммиту>"*. Сообщения к коммиту писать ***ОБЯЗАТЕЛЬНО***!

## Просмотр наличия изменений
Для того, чтобы посмотреть имеются ли изменения в локальном репозитории используется команда *git status*. Достаточно её просто применить в папке с препозиторием

## Просмотр разницы между текущей версией и последней "сохранённой"

Для того, чтобы посмотреть разницу между последним коммитом и текущей версией файлов, используется команда *git diff*. Достаточно её просто применить в папке с репозиторием

## Просмотр истории коммитов

Для просмотра истории коммитов используется команда *git log*. Для того, чтобы увидеть историю коммитов, достаточно просто применить эту команду в папке с репозиторием.

## Перемещения между изменениями

Для того, чтобы переместиться на какое-то из прошлых изменений необходимо использовать команду *git checkout*. Применяется она следующим образом в папке с репозиторием: *git checkout <номер коммита>*. Для возврата к последнему коммиту ветки нужно использовать команду *git checkout master*

## Работа с ветками


### Просмотр списка веток

Для того, чтобы просмотреть список имеющихся веток, необходимо использовать команду *git branch*. Для этого в папке с репозиторием пишем команду *git branch*.

### Создание новой ветки

Для того, чтобы создать новую ветку, необходимо использовать команду *git branch*. Используется она в папке с репозиторием следующим образом: *git branch <название новой ветки>* 

## Слияние веток

Для слияния веток используется команда *git merge*. Приняется она в папке с репозиторием следующим образом: *git merge <название ветки>*. В процессе слияния может произойти ***КОНФЛИКТ*** или слияние может произойти автоматически

## как завтра будем просыпаться?

# Инстукция по рабоет с GIT

## Что такое Git
***Git*** - это одна из реализаций распределенной системы контроля версий, поддерживающие как локальные, так и удаленные репозитории. Самая популярная реализация Git - это [GitHub](https://github.com)

## Поготовка репозитория
Для создания репозитория используется команда "git init". Для этого необходимо открыть в терминале папку с будущим репозиторием и там написать "git init".

## Создание коммитоа

### Выполнения коммита
Для того, чтобы выполнить коммит используется команда "git commit". Для этого в терминале с папкой-репозиторием необходимо написать "git commit -m "<сообщение к коммиту>"". Сообщение к коммиту писать ***ОБЯЗЯТЕЛЬНО!!!*** .

## Добавление файла к комиту
Для добавления файла к коммиту используется команда "git add". Для этого в терминале с папкой - репозиторием необходимо написать "git add <название файла>.

## Журнал изменений 
Для просмотра журнала коммитов используется команда "git log". Для этого в терминале с папкой-репозитории пишем "git log". В показанном журнале обязательно будут:
* Хэш коммита 
* Дата и время коммита
* Автор коммита
* Текст сообщения к коммита

## Перемещение между  коммитами
Для перемещения между комитами используется команда "git checkout". Для этого в терминале с папкой-репозиторием необходимо написать "git checout <хэш коммита>". Хэш коммита можно взять из истории коммитов.

## Ветки в Git
Для создания веток используется команда "git branch". Для этого в терминале с папкой-репозиторием необхлдимо написать "git branch <название ветки>". Перемещение между ветками используется команда "git checkout", так же, как при перемещение между коммитами. 

## Слияние веток и разрешение конфликтов
Для слияния веток импользуется команда "git merge". Для этого в терминале с папкой-репозиторием необхлдимо написать "git merge <название ветки>". Конфликты могут произойти при запуске слияния и во время процесса слияния. 

## Удаление веток
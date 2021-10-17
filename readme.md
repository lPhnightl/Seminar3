# Инструкция по работе с Git и Github

## Что такое Git?
**Git** - одна из реализаций распределнных систем контроля версий, Позволяет контролировать версионность файлов как локально, так и на удалённом сервере. Самая популярная система контроля версий.



## Подготовка репозитория 
**Репозиторий** - это хранилище файлов, поддерживающие версионность. Создать репозиторий в папке можсно с помощью команды *git init*, приминив эту команду в папке с будущем репозиторием 


## Создание "сохранений" 
Создать "сохранения" они же фиксация или коммиты, мы можем с помощью команды *git commit*. Для этого необходимо написать команду *git commit -m <сообщение к коммиту>* сообщение к коммиту писать обязательно. Все файлы должны быть добавлены в коммит с помощью команды *git add*. если файлы не добавлены, то можно использовать флаг *-а* и команды  

## Журнал изменений 

## Перемещение между "сохранениямми"
Для переключения между "сохранениями" (коммитами), необходимо использовать команлу *git checkout* следующим образом: *git checkout <номер коммита для переключения>*.
команды *git reset* и *git revert* позволяют отменять измениня. Команда *git revert* возвращает к указанному коммиту, создавая новый коммит, а команда *git reset* возвращает к указанному коммиту и затирает историю изменений до указанного коммита.

## Ветки в Git
Ветки git позволят создавать разветвления, то есть работать с одним и тем же содержимым в разных его версиях. Посмотреть список имеющихся веток можно с помощью команды *git branch*? а создать новую ветку 

## Слияние веток и решение конфликтов 


## Удаление веток
Для того, чтобы удалть уже слитую ветку используется команда *git branch -d <branch name>*

## Скачивание с удалённого репозитория 
 Слияние веток происходит с помощью *git clone* 

## 

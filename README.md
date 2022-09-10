![logo](https://raw.githubusercontent.com/linkghm/linkghm/master/src/git.svg)
# Инструкция по Git

## Что такое Git?

Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире. 

## Первоначальные настройки:

Перед началом работы нужно выполнить некоторые настройки:

> _git config --global user.name "Your Name"_  # указать имя, которым будут подписаны коммиты

> _git config --global user.email "e@w.com"_   # указать электропочту, которая будет в описании коммитера

Если вы в Windows:

> _git config --global core.autocrlf true_  # включить преобразование окончаний строк из CRLF в LF

## Подготовка репозитория

Для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием.

## Git add

Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add*, напишите *git add "имя файла"*

## Создание коммитов 

Для того чтобы создать коммит (сохранение),необходимо выполнить команду *git commit -m "Сообщение"*

## Создание ветки

Для того,чтобы создать ветку, нужно использовать *git branch имя_ветки* или *git checkout -b имя_ветки*

## Клонирования репозитория
Для клонирования удаленного репозитория в одноименную локальную директорию, вводим *git clone адрес_репозитория*


## Отправка изменений в удалённый репозиторий
Отправляем коммит с быстрым критическим изменением в master в удалённом репозитории 
*git push*

## Получение изменений из удалённого репозитория
Для загрузки изменений из удалённого репозитория используется параметр pull. Он скачивает копию текущей ветки с указанного удалённого репозитория и объединяет её с локальной копией.
*git pull*

## Переключение веток
Команда *git checkout* позволяет перемещаться между ветками, созданными командой *git branch*. 
Перейти на ветку можно командой *git checkout имя_ветки*

> Более подробно можно прочитать в [справочнике](https://docs.microsoft.com/ru-ru/contribute/markdown-reference)
# __Работа с MarkDown__ #

## __Начало работы с репозиторием:__ 

чтобы начать работать с репозиторием - необходимо ввести комманду 

* __git init__

Если работаем с репозиторрием первый раз - необходимо задать имя и почту

* __git config --global user.name some_name
* __git config --global user.email some_name@mail.com

## __Основные комманды__ ##

Чтобы добавить файл нужно ввести коммаду на добавление с указанием имени файла

* __git add file_name__

Чтобы зафиксировать добавление необходимо ввести:
* __git commit -m "message"__

добавление тега -а - позволяет указать коммит для всех файлов папки
* __git commit -a -m "message"__

Чтобы проверить состояние репозитория:

* __git status__

Чтобы вывести историю коммитов:

* __git log__

Для перехода с одной версии на другую необходимо ввести команду с добавлением первых 4х знаков номера сохраненной версии

* __git checkout xxxx__

чтобы вернуться на прежнее состояние необходимо ввести команду

* __git checkout master__

Чтобы увидеть разницу между текущей версией и сохраненной, необходимо ввести команду:

* __git diff__

Она выведет на терминале измененные, но незакоммиченные строки

Чтобы добавить картинку, необходимо:
* __![текст, если картинка не прогрузиться](имя файла или путь)__

например:

![картинка MD](picture.jpg)

## _Выделение текста. Заголовки"_ ##

Чтобы задать для текста полужирное начертание, заключите его в  **двойные звездочки**: ** __ **

Чтобы задать для текста курсивное начертание, заключите его в *одинарные звездочки*: * __ *

Чтобы задать для текста полужирное и курсивное начертание, заключите его в ***тройные звездочки*** : *** ___ ***

## Цитаты ##

Для обозначения цитат в языке используется знак «больше» («>»).

> Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа.

Вложение цитаты в цитату: для такой разметки используются дополнительные уровни знаков цитирования («>»)

> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования


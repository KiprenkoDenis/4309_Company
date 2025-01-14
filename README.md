# Синтаксис языка Маркдаун

## Варианты текста

Чтобы выделить текст полужирным, нужно выделить его двумя * с обеих сторон, например **вот так**

Чтобы выделить текст курсивом, нужно выделить его * с обеих сторон, например *вот так*

Чтобы зачеркнуть текст, нужно выделить его двумя ~  с обеих сторон, например ~~вот так~~

## Списки

Ненумерованные списки обозначаются * в начале строки, вот так

* элемент 1

* элемент 2

* элемент 3

Нумерованные списки обозначают обычными цифрами, вот так

1 первый элемент

2 второй элемент 

3 третий элемент

Вложенные списки обозначают отступом.

## Добавление цитат

Для обозначения цитат в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа. Также синтаксис Markdown позволяет создавать вложенные цитаты (цитаты внутри цитат). Для их разметки используются дополнительные уровни знаков цитирования («>»). Цитаты в Markdown могут содержать всевозможные элементы разметки. Цитаты в языке Markdown выглядят следующим образом:

>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.

>Это пример цитаты,
в которой угловая скобка
ставится только перед началом нового параграфа.
>Второй параграф.

## Ссылки

  Для создания внутритекстовой ссылки необходимо использовать круглые скобки сразу после закрывающей квадратной. Внутри них необходимо поместить URL-адрес. В них же возможно расположить название, заключенное в кавычки, которое будет отображаться при наведении, но этот пункт не является обязательным.

   [синтаксис Markdown](https://gist.github.com/Jekins/2bf2d0638163f1294637#Blockquotes)

## Работа с изображениями

Чтобы вставить картинку, нужно использовать команду 

![Это моя собака](Deyzi.jpg)

## Работа с таблицами

Самый простой и быстрый способ как сделать таблицу в markdown - это использовать Генератор Маркдаун Таблиц или сервис от AnyWayData.

С другой стороны, синтаксис языка маркдаун достаточно простой, чтобы можно было нарисовать таблицы самому. Для этого используются символ pipe или вертикальной черты ( | ) для разделения ячеек и дефиса ( - ) для создания строки заголовка.

Вот пример таблицы:

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1    | Cell 2   | Cell 3   |
| Row 2    | Cell 5   | Cell 6   |
| Row 3    | Cell 8   | Cell 9   |

## Горизонтальные разделительные линии

Для того чтобы создать горизонтальную линию с использованием синтаксиса языка Markdown, необходимо поместить три (или более)дефиса или звездочки на отдельной строке текста. Между ними возможно располагать пробелы. Горизонтальные линии в Markdown выглядят следующим образом:

Первая часть текста, который необходимо разделить
***
Вторая часть текста, который необходимо разделить
Или

Первая часть текста, который необходимо разделить

---

Вторая часть текста, который необходимо разделить

## Дополнение по GIT 

git init - инициализирует новый репозиторий Git в текущей директории.

git clone [url] - создает локальную копию удаленного репозитория по указанному URL-адресу.

git add [file] - добавляет файлы в индекс для последующих коммитов.

git commit -m "commit message" - создает новый коммит с сообщением описания изменений.

git status - показывает текущее состояние рабочей директории и индекса.

git push - отправляет изменения из локального репозитория на удаленный репозиторий.

git pull - обновляет локальный репозиторий до последней версии из удаленного репозитория.

git branch - показывает список всех веток в репозитории.

git checkout [branch] - переключается на указанную ветку.

git merge [branch] - объединяет указанную ветку с текущей веткой.

git log - показывает список коммитов в репозитории.

git diff - показывает различия между локальными изменениями и последней версией из удаленного репозитория.

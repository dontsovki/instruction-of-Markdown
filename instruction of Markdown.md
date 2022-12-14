# инструкция по работе с Git, используя возможности Markdown

Git — самая популярная система контроля
версий, но не единственная. Алгоритм
работы подобных систем схож

# Основные команды:

1. git log — вызывать список действий и сохранений,
2. git init — создать репозиторий в папке на локальной машине,
3. git add — отслеживать добавленные файлы,
4. git commit + комментарий — сохранить текущее состояние,
5. git diff — показать разницу между версиями,
6. git chechout — переключиться между разными версиями.
7. git branch -d “Название ветки” - удаление ветки
8. git ignore - Чтобы исключить ненужные файлы
из загрузки
9. git log --graph - Ключ -graf в связке с командой log позволяет отобразить коммиты в виде дерева.
10. git merge <имя ветки для слияния с текущей> - Чтобы слить любую ветку с текущей
11. git --version - проверим текущую установленную
версию пограммы
12. git status - Показывает текущее состояние гита, есть
ли изменения, которые нужно закоммитить
(сохранить)
13. git commit -m - зафиксировать или сохранить
14. git branch - Создать ветку. Делать это надо в папке с репозиторием:
15. git push - команда добавления в репозиторий на Git hub
16. git pull - команда добавления из репозитория на Git hub
17. cd (директория репозитария указанный в исходной папке) - команда изменения директории
18. git clone https://github.com/ilnar-geekbrains/version_control_lection_3.git - команда добавления кода в git

# Выделение теста

1. Жирный текст — (**) или (__) (**пример**), (__пример__)
2. Курсивный текст — (*) или (_) (*пример*)
3. Текст, выделенный курсивным полужирным шрифтом - *** (***пример***)

Альтернативные способы выделения необходимы, для того что бы могли совмещать два, три способа например. __текс может быть жирным и *курсивным*__

# Списки

Markdown поддерживает упорядоченные (нумерованные) и неупорядоченные (ненумерованные) списки. Для формирования неупорядоченный списков используются такие маркеры, как звездочки, плюсы и дефисы. Все перечисленные маркеры могут использоваться взаимозаменяемо. Для формирования упорядоченных списков в качестве маркеров используются числа с точкой. Важной особенностью в данном случае является то, что сами номера, с помощью которых формируется список, не важны, так как они не оказывают влияния на выходной HTML код. Как бы ни нумеровал пользователь список, на выходе он в любом случае будет иметь упорядоченный список, начинающийся с единицы (1, 2, 3…). Эту особенность стоит учитывать в том случае, когда необходимо использовать порядковые номера элементов в списке, чтобы они соответствовали номерам, получающимся в HTML. Упорядоченные списки всегда следует начинать с единицы. Маркеры списков обычно начинаются с начала строки, однако они могут быть сдвинуты, но не более чем на 3 пробела. За маркером должен следовать пробел, либо символ табуляции. При необходимости в список можно вставить цитату. В этом случае обозначения цитирования ( «>» ) нужно писать с отступом. Упорядоченные списки выглядят следующим образом:

	Проводник
2.	Полупроводник
3.	Диэлектрик
Неупорядоченные списки выглядят следующим образом:

* Проводник
* Полупроводник
* Диэлектрик
Или

- Проводник
- Полупроводник
- Диэлектрик
Или

+ Проводник
+ Полупроводник
+ Диэлектрик
На выходе всех трех перечисленных вариантов имеется один и тот же результат. В результате на экран выводится следующее:

Проводник
Полупроводник
Диэлектрик
и

Проводник
Полупроводник
Диэлектрик
Цитата, вставленная в список, выглядит следующим образом:

1. Элемент списка с цитатой:

    > Это цитата
    > внутри элемента списка.

 2. Второй элемент списка

 При вставке цитат в элементы списка важно учитывать, что элементы списка должны находиться на одном уровне, а цитаты должны указываться с отступом. В случае, если правило с единым уровнем списка не соблюдается, следующий после цитаты элемент списка будет автоматически нумероваться цифрой «1.». Кроме того, при необходимости в список можно вставить исходный код. В этом случае его нужно писать с двойным отступом – 8 пробелов или 2 символа табуляции.

Элемент списка, содержащий исходный код

 <исходный код >  
Блоки кода
Отформатированные блоки кода используются в случае необходимости процитировать исходный код программ или разметки. Для создания блока кода в языке Markdown необходимо каждую строку параграфа начинать с отступа, состоящего из четырех пробелов или одного символа табуляции. Блок кода продолжается до тех пор, пока не встретится строка без отступа (или конец текста). Внутри блока кода амперсанды («&») и угловые скобки («<» и «>») автоматически преобразуются в элементы HTML разметки. Кроме того, следует отметить, что внутри блоков кода обычный синтаксис Markdown не обрабатывается. Блок кода в Markdown выглядит следующим образом:

Это обычный параграф:

Это блок кода
Горизонтальные линии (разделители)
Для того чтобы создать горизонтальную линию с использованием синтаксиса языка Markdown, необходимо поместить три (или более)дефиса или звездочки на отдельной строке текста. Между ними возможно располагать пробелы. Горизонтальные линии в Markdown выглядят следующим образом:

Первая часть текста, который необходимо разделить
***
Вторая часть текста, который необходимо разделить
Или

Первая часть текста, который необходимо разделить

---

Вторая часть текста, который необходимо разделить
В результате на экран выводится следующее:

Первая часть текста, который необходимо разделить

Вторая часть текста, который необходимо разделить

При использовании данного инструмента важно помнить, что после первой части текста и перед второй необходимо оставлять пустую строку. Данное правило необходимо соблюдать только при использовании дефисов. Если его не соблюдать, на экран будет выведен заголовок второго уровня и строка обычного текста. При использовании символа звездочки данным правилом можно пренебречь.

# Работа с изображениями

В Markdown существует 2 способа вставки изображений в документ:
a. С помощью непосредственного указания URL-адреса изображения. Синтаксис данной команды выглядит следующим образом:
![Альтернативный текст](путь к кизображению.jpg)

b. С помощью метки-идентификатора. Синтаксис данной команды записывается следующим образом:
![текст][id]

# Ссылки
Markdown поддерживает два стиля оформления ссылок:

Гиперссылка, с немедленным указанием адреса (внутритекстовая);
Гиперссылка, подобная сноске.

Подразумевается, что помимо URL-адреса существует еще текст ссылки. Он заключается в квадратные скобки. Для создания внутритекстовой гиперссылки необходимо использовать круглые скобки сразу после закрывающей квадратной. Внутри них необходимо поместить URL-адрес. В них же возможно расположить название, заключенное в кавычки, которое будет отображаться при наведении, но этот пункт не является обязательным.

[пример](http://alkor-expert.ru/ "Необязательная подсказка")

При создании сносной гиперссылки вместо целевого адреса используется вторая пара квадратных скобок, внутри которых помещается метка, идентификатор ссылки (id).

В этом случае возможно определить идентификатор в любом месте документа:

[id]: http://alkor-expert.ru "Необязательная подсказка"

В результате на экран выводится следующее: [пример] [id] [id]: http://alkor-expert.ru "Необязательная подсказка" Иными словами, она состоит из следующих элементов:

Идентификатор ссылки, окружённый квадратными скобками (которым может предшествовать необязательный отступ от одного до трёх пробелов);
Двоеточие;
Один или несколько пробелов (или символов табуляции);
URL гиперссылки;
Необязательный заголовок (подсказка к изображению, которая всплывает при наведении на него) гиперссылки, заключённый либо в двойные или одиночные кавычки, либо в скобки.


# Цитаты

Цитаты
Для обозначения цитат в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа. Также синтаксис Markdown позволяет создавать вложенные цитаты (цитаты внутри цитат). Для их разметки используются дополнительные уровни знаков цитирования («>»). Цитаты в Markdown могут содержать всевозможные элементы разметки. Цитаты в языке Markdown выглядят следующим образом:

>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.

>Это пример цитаты,
в которой угловая скобка
ставится только перед началом нового параграфа.
>Второй параграф.
Вложение цитаты в цитату выглядит следующим образом:

> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования
>
>Первый уровень цитирования

# Заголовки

Язык разметки Markdown поддерживает 2 стиля обозначения заголовков: подчеркивание и выделение символом («#»). Выделение заголовков с помощью подчеркивания производится знаками равенства («=») в случае, если заголовок первого уровня, и дефисами («-») в случае, если заголовок второго уровня. Количество знаков подчеркивания не ограничивается. При выделении заголовков с помощью символа («#») используется от одного до шести данных символов, которые устанавливаются в начале строки (перед заголовком). В данном случае количество символов соответствует уровню заголовка. Кроме того, заголовок возможно снабдить закрывающимися символами («#»), хотя это и не является обязательным. Количество закрывающихся символов не обязано соответствовать количеству начальных символов. Уровень заголовка определяется по количеству начальных символов.
Заголовки первого и второго уровней, выполненные с помощью подчеркивания, выглядят следующим образом:

Заголовок первого уровня
========================
Заголовок второго уровня
-------------------------
Заголовки первого, третьего и шестого уровней, выполненные с помощью символа («#»), выглядят следующим образом:

#  Заголовок первого уровня
### Заголовок третьего уровня
###### Заголовок шестого уровня
Приведенные выше заголовки, выполненные с помощью символа («#») тождественны следующим:

#  Заголовок первого уровня #
### Заголовок третьего уровня ###
###### Заголовок шестого уровня ######

# Заключение
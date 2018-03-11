# Популярная детская игра, Виселица
https://ru.wikipedia.org/wiki/Виселица_(игра)
Игроку предлагается отгадать слово, загаданное программой, поочердно предлагая буквы. Для наглядности, статус игры отображется схематичной виселицей с петлёй.

Загаданное слово является именем существительным, нарицательным в именительном падеже единственного числа, либо множественного числа при отсутствии у слова формы единственного числа.

Если предлагаемая буква есть в слове, то программа отобразит ее соответсвующее положение в слове чертами — столько раз, сколько она встречается в слове. Если такой буквы нет, то к виселице добавляется элемент, изображающий голову. Игрок продолжает отгадывать буквы до тех пор, пока не отгадает всё слово. За каждый неправильный ответ  добавляется одна часть туловища к виселице.

Если туловище в виселице нарисовано полностью, то  игрок проигрывает, считается повешенным. 

https://ru.wikipedia.org/wiki/Виселица_(игра)
## Требования:
ruby версии 2 и выше
## Поддерживаемые языки(support language):
Только русский (russian only)
## Запуск:  
```
ruby viselitsa.rb
```
## Примечание
Вы можете самостоятельно добавить слова, загадываемые программой, добавив их в файл ./data/words.txt

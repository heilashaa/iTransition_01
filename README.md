# [iTransition](https://itransition.by/) `training Jan,2020`
## Author: [Alexandr Heilash](https://www.linkedin.com/in/alexandr-heilash-6b0055173/)
### Task #1

Решения присылайте на мыло `p.lebedev@itransition.com` в виде ссылки на Dropbox на файл `permutations.js` (нужна именно public-ссылка, аттачи или ссылки куда-то еще приниматься не будут, так как решения проверяются скриптом).

Требуется разработать на языке JavaScript код, печатающий на консоль наибольшее число строк из переданных, которые являются перестановками друг друга. Если ни одна из строк не является перестановкой другой (например, была передана только одна строка или строки содержат уникальные символы), напечатать одну из строк. Если не было передано ни одной строки, ничего не выводить. При существовании нескольких решений — напечатать одно решение (любое). Вывод всегда сопровождается переводом строки, каждая строка выводится на отдельной строке. Ограничения (то, что будет проверяться, не нужно ограничения запиливать в свой код): длина одной строки не превосходит 256 символов, количество строк не превосходит 64, строки содержат только латинские буквы и арабские цифры, время выполнения одного теста - не более 10 секунд, вывод не содержит посторонних символов.
Решение будет приниматься при прохождении набора тестов, результат будет оцениваться исходя из размера файла в байтах (меньше — лучше). Обратите внимание, что это код-гольф, нужно ужать код в минимальное число байтов.
````
Пример:

node permutations.js ABCDE EDBCA XYZ ZYX ZXY
XYZ
ZYX
ZXY

Несколько возможных тестов (в случае существования нескольких решений вывод может отличаться в соответствии с условием задачи):

node permutations.js 132 123 123 132 XYX YXZ YXZ
132
123
123
132
node permutations.js ABCDEFGH ABDEC ABCDEFG ABCEDF ABCED
ABDEC
ABCED
node permutations.js ABCDEFGH ABCDEFG ABCEDF ABCED HGFEDCAB
ABCDEFGH
HGFEDCAB
node permutations.js ABCDEFGH 123 321
123
321
node permutations.js A BCDEFGH ABCDEFG ABCDEF ABCDE EDCBA A A
A
A
A
node permutations.js ABCDEFGH ABCDEFG ABCDEF ABCDE EDCBCA
ABCDEFGH
node permutations.js
node permutations.js ABCDEFGH
ABCDEFGH

<h3>Как открыть подарок-то?</h3>
<strong>Чтобы получить подарок, Вам нужно расшифровать ключ от сейфа.</strong>
Сначала расшифруйте текст <strong>vigener.txt</strong>, ключом от которого является <code>*ключ от виженера внизу написан*</code>, затем расшифруйте файл <strong>vertical.txt</strong>, ключом от которого будет самое распространенное слово из 4-х букв в предыдущем тексте.
Алфавит для виженера я напишу снизу, чтобы Вы смогли расшифровать побыстрее)
Когда вы расшифруете вертикалочку, обратите внимание на последнее предложение текста, - там будет храниться ключ к сейфу :) 

<h4>Ключ для Виженера:</h4>
<strong>Правильный ответ и будет ключом от шифра Виженера.</strong>

В самый нужный момент для ухода Арины и Насти из компании, вы по звонку становитесь:
- АлексейВладимирович
- АлексейМаксимович
- АлексейВикторович

<h4>Алфавит для Виженера:</h4>
```python
n = ord("а")
alphabet = [chr(i) for i in range(n, n+32)]
n = ord("А")
alphabet += [chr(i) for i in range(n, n+32)]
```
<h4>Вид ключа для Вертикальной перестановки:</h4>
Представим, что ключ - это слово <code>*книга*</code>, тогда в Python мы представим его как ```[3, 4, 2, 1, 0]```, т.е. в порядке появления в алфавите.

<h4>P.S.</h4>
Все файлы, кстати, лучше открывать с параметром <code>encoding="utf-8"</code>, а то билеберда выйдет.

<strong>Удачи!</strong>

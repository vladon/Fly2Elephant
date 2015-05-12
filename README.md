# Описание
Приложение *Fly2Elephant* призвано помочь в решении одной из самых сложных задач, которая формулируется следующим образом: `как из мухи сделать слона?`.

# Постановка задачи
Дано исходное и конечное слово равной длины. Длина исходных слов не ограничена. Необходимо составить цепочку слов от исходного слова до конечного. Каждое следующее слово в цепочке может отличаться от предыдущего только одной буквой. Исходное, конечное и все промежуточные слова должны состоять из одинакового количества букв. Все используемые слова обязательно должны содержаться в заранее определенном словаре. Цепочка слов должна быть наименьшей длины из всех возможных.

На вход в программу подается:
 1.	Путь к текстовому файлу, в котором указано начальное и конечное слово. На первой строке указано начальное слово, на второй строке конечное.
 2.	Путь к файлу, который содержит словарь. Слова в словаре указаны по одному на каждой строке. В словаре слова могут быть разной длины.

На выходе программа должна вывести в консоль путь от исходного слова к конечному, по одному слову на одной строке.

# Ограничения
Файлы, которые подаются на вход программы, должны быть сохранены в кодировке **UTF8 без BOM**.
Также преполагается, что в системе присутствует локаль **ru_RU.utf8**.

# Пример запуска
`user@Ubuntu-x64-Eclipse:~/workspace/Fly2Elephant$ Fly2Elephant words.txt dic.txt`

# JAVA_HT_2

Ставцев Максим Александрович БПИ-217


На вход данной программе пользователем подаётся полный путь к корневой директории.
Формат пути показан пользователю в консоли.

Далее программа ищет файлы в корневой и вложенных директориях. Поиск происходит по файлам без указанного расширения. Пример такой структуры в архифе Example.
В данных файлах она находит соответствие паттерну require. 
Корректными входными данными считаются директивы require, в которых указан полный путь от корневой директории к необходимому файлу.

После обнаружения всех зависимостей программа производит топологическую сортировку файлов, выводит зависимости в консоль, вместе с объединённым
содержанием файлов, оно также выводится в результирующий файл resultText.txt в корневой директории.

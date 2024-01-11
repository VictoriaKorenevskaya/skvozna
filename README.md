Входной и выходной файл могут быть следующих форматов: plain text, xml, json. Так же входные и выходные файлы могут быть архивированы и зашифрованы, разными engines (только архивирован, только зашифрован, сперва архивирован, а потом зашифрован и наоборот).
 
«Тип» входного и выходного файла задаются параметрами консоли.
Приложение реализовать двумя способами: без использования Design Patterns и c использованием Design Patterns (Decorator и Builder), сравнить реализации.
 
Обработка информации на первом этапе: найти все арифметические операции во входном файле и заменить на результаты в выходном файле.
Реализовать фильтрацию двумя способами без использования регулярных выражений и с использованием регулярных выражений (а так же третьим :) найти библиотеку, которая все делает за вас, парсинг и калькуляцию, такие есть и не одна). Провести сравнительный анализ 2-х вариантов реализации.
 
Примеры атомарных подзадач:
Чтение \ запись текстовый файл;
Чтение \ запись xml файл (используя специальный API для чтения XML и не используя – чтение по строчно);
Чтение \ запись json файл (используя специальный API для чтения XML и не используя – чтение по строчно);
Архивация \ де Архивация файла используя ту или иную реализацию Zip;
Архивация \ де Архивация файла используя ту или иную реализацию Rar;
Шифровка \ де Шифровка файла используя любую библиотеку шифрования;
Покрыть все эти атомарные задачи Unit Test-ами;

![1000008900-02](https://github.com/VictoriaKorenevskaya/skvozna/assets/137886237/9b596fd6-7269-4db2-9071-1b0288bd8c06)

# file_uploader
Необходимо было организовать хранение накладных на сервере в формате pdf.
Данный скрипт решает эту задачу и организовывает процесс таким образом:
1. Файл проверяется на соответствие формату.
2. Для упорядоченного хранения используется дерево каталогов: год/ месяц / число.
3. Проверяется существование дерева каталогов на текущее число и если такого нет, то создается.
4. Файл переименовывается в, сгенерированый для него, md5 хэш.
5. Файл переносится из временной папки на сервер. 
6. Данные о полном пути и оригинальном названии файла записываются в БД.
7. profit!

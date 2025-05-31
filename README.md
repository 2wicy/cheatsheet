# cheatsheet
man date — показать дополнительную информацию про команду date ;
clear — очистить консоль;
exit — закрыть консоль;
pwd — показать, в какой ты папке;
ls — показать файлы в папке, где ты сейчас;
ls -a — показать файлы и папки, включая скрытые;
cd first-project — перейти в папку first-project;
cd first-project/qa — перейти в папку qa, находящуюся в папке first-project;
cd .. — перейти на уровень выше в родительскую папку;
cd ../.. — перейти на два уровня выше;
cd / — перейти в корневую директорию;
cd ~ — перейти в домашнюю директорию;
mkdir second-project — в текущей папке создать папку с именем second-project;
rm about.html — удалить файл about.html;
rmdir images — удалить папку images;
rm -r second-project — удалить папку second-project и всё, что она содержит;
touch Main.java — создать файл Main.java в текущей папке;
touch Main.java Cat.java — если нужно создать несколько файлов, их имена
можно вводить через пробел;
nano logs/2020/1/apache
_
2020-01-01.txt — открыть текстовый файл apache_2020-
01-01.txt;
echo "Who's morty?" — вывести в окно терминала строку Who's morty?
echo "text" > filename — записать строку text в файл filename;
Шпаргалка: консоль 1
echo "Who's morty?" > ~/logs/2020/1/secrets.txt — записать строку Who's morty? в
файл secrets.txt;
cat ~/logs/2020/1/apache
_
2020-01-01.txt — вывести содержимое в окно терминала;
cat a.txt > b.txt — перезаписать содержимое файла a.txt в b.txt;
cat a.txt >> b.txt — скопировать содержимое файла a.txt в конец b.txt;
cp brothers.html sisters.html — скопировать файл brothers.html и назвать новый
файл sisters.html;
cp ../docs/brothers.html ../Documents/ — скопировать brothers.html в папку
Documents;
mv card.txt ~/ — перенести card.txt из текущей директории в домашнюю;
mv my_
app.ssh your
_
app.ssh — переименовать файл my_app.ssh в your_app.ssh;
grep DELETE apache
_
2020-01-01.txt — вывести все строки из файла apache_2020-
01-01.txt, которые содержат DELETE;
grep -R DELETE ~/logs/2020/1 — вывести все строки внутри каталога, которые
содержат DELETE;
grep -n DELETE apache
_
2020-01-01.txt — вывести все строки и их номера из файла
apache_2020-01-01.txt, которые содержат DELETE.

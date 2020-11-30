# SwEng_2020

Последовательность шагов, которые надо выполнить в Bash. Курсивом выделены параметры, вместо которых вы должны подставить свои данные.
1.	Создать новую папку, запустить в ней Bash:
* В проводнике — правой кнопкой мыши щёлкнуть на папке и в контекстном меню выбрать «Git Bash Here», либо
*	Запустить «Git Bash» и перейти в папку командой
		$ cd <путь>
2.	Установить информацию о себе: имя (фамилия + имя, латинницей)
$ git config --global user.name "_Adigeyev MG_"
$ git config --global user.email "_adimg-pi@yandex.ru_"
3.	Cоздать клон проекта SwEng_2020.  Адрес: https://github.com/adimg-pi/SwEng_2020.git 
$ git clone https://github.com/adimg-pi/SwEng_2020 
4. В bash перейдите в папку SwEng_2020 (она была создана в результате клонирования проекта из репозитория):
      $ cd SwEng_2020
5. В файл Students.txt в конец добавить блок:
	Name: свои фамилия и имя, латинницей
	Added: дата и время в формате DD.MM.YYYY HH:mm
4.  Просмотреть статус файлов и изменения, внесённые в файл:
	$ git status
	$ git diff
5	Сделать скриншот окна Bash и сохранить в каталог проекта под своей фамилией (латинницей): _Adigeyev_.png
6	Зафиксировать изменения, с комментарием "added  <Фамилия>" (всё латинницей):
	$ git add Students.txt
	$ git add _Adigeyev_.png
	$ git commit -m "added _Adigeyev_"
Важно: при указании имён файлов обязательно соблюдайте различие заглавных и строчных букв.

7	Загрузить изменения в общей репозиторий проекта
	$ git push
	Потребуется ввести логин и пароль для доступа к репозиторию GitHub.

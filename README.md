# XML
 21. Создать внешний репозиторий c названием XML.
click new for creating repository
 22. Клонировать репозиторий XML на локальный компьютер.
git clone link  
cd XML
 23. Внутри локального XML создать файл “new.xml”.
touch new.xml
 24. Добавить файл под гит.
git add new.xml
 25. Закоммитить файл.
git commit -m "add XML file"
 26. Отправить файл на внешний GitHub репозиторий.
git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
cat >> new.xml
<req>
	<name>Pavlo</name>
	<surname>Mandiuk</surname>
	<age>36</age>	
	<pets>0</pets>
	<salary>400$</salary>
</req>

 28. Отправить изменения на внешний репозиторий.
git add new.xml
git commit -m "changes"
git push
 29. Создать файл preferences.xml
touch preferences.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
cat >> new.xml
<req>
	<film>Star Wars</film>	
        <serial>Star Treck</serial>
        <food>Borsch</food>
        <season>Summer</season>
        <country>Canada</country>
</req>
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
cat >> skills.xml
<req>
        <skills>Bash</skills>
        <skills>Git</skills>
        <skills>Postman</skills>
        <skills>SQL</skills>
        <skills>Manual testing</skills>
</req>

 32. Сделать коммит в одну строку.
git add preferences.xml skills.xml ; git commit -m "add two more files"
 33. Отправить сразу 2 файла на внешний репозиторий.
git push
 34. На веб интерфейсе создать файл bug_report.xml.
add file 
create new file
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit new file
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
Edir this file
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes
 38. Синхронизировать внешний и локальный репозиторий XML
git fetch
git pull

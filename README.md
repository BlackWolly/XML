		# XML
		Создать внешний репозиторий c названием XML.
		click new for creating repository
		Клонировать репозиторий XML на локальный компьютер.
		git clone link  
		cd XML
		Внутри локального XML создать файл “new.xml”.
		touch new.xml
		Добавить файл под гит.
		git add new.xml
		Закоммитить файл.
		git commit -m "add XML file"
		Отправить файл на внешний GitHub репозиторий.
		git push
		Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
		cat >> new.xml
		<req>
			<name>Pavlo</name>
			<surname>Mandiuk</surname>
			<age>36</age>	
			<pets>0</pets>
			<salary>400$</salary>
		</req>

		Отправить изменения на внешний репозиторий.
		git add new.xml
		git commit -m "changes"
		git push
		Создать файл preferences.xml
		touch preferences.xml
		В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
		cat >> new.xml
		<req>
			<film>Star Wars</film>	
 		        <serial>Star Treck</serial>
  		        <food>Borsch</food>
  		        <season>Summer</season>
   		        <country>Canada</country>
		</req>
		Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
		cat >> skills.xml
		<req>
      		  <skills>Bash</skills>
      		  <skills>Git</skills>
      		  <skills>Postman</skills>
      		  <skills>SQL</skills>
       		  <skills>Manual testing</skills>
		</req>
		Сделать коммит в одну строку.
		git add preferences.xml skills.xml ; git commit -m "add two more files"
		Отправить сразу 2 файла на внешний репозиторий.
		git push
 		На веб интерфейсе создать файл bug_report.xml.
		add file 
		create new file
		Сделать Commit changes (сохранить) изменения на веб интерфейсе.
		Commit new file
		На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
		Edit this file
		Сделать Commit changes (сохранить) изменения на веб интерфейсе.
		Commit changes
		Синхронизировать внешний и локальный репозиторий XML
		git fetch
		git pull

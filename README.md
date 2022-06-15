# XML
GIT Homework 1

XML

 21. Создать внешний репозиторий c названием XML.

Repositories ==> New ==> Repos Name:XML ==> Check "Add a README file" ==> Press "Create repository"

 22. Клонировать репозиторий XML на локальный компьютер.

git clone  rep_link

 23. Внутри локального XML создать файл “new.xml”.

touch new.xml

 24. Добавить файл под гит.

git add new.xml

 25. Закоммитить файл.

git commit -m "add new.xml"


 26. Отправить файл на внешний GitHub репозиторий.

git push

 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

cat > new.xml

<?xml version="1.0" encoding="utf-8"?>

<information_about_yourself>

	<full_name>Trushin Nikita Andreevich </full_name>
  
	<age>29</age>
  
	<number_of_pets>0</number_of_pets>
  
	<future_desired_salary>1000</future_desired_salary>
  
</information_about_yourself>

#ctrl+c

 28. Отправить изменения на внешний репозиторий.

git add new.xml

git commit -m "add info in new.xml "  

git push

 29. Создать файл preferences.xml

touch preferences.xml

 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

cat >preferences.xml

<?xml version="1.0" encoding="utf-8"?>

<my_preferences>

		<favorite_movie>Saw</favorite_movie>
    
		<favorite_series>Ozark</favorite_series>
    
		<favorite_food>kebab</favorite_food>
    
		<favorite_time_of_year>summer</favorite_time_of_year>
    
		<country_i_would_like_to_visit>Japan</country_i_would_like_to_visit>
    
</my_preferences>
#ctrl+c

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

cat >skills.xml

<?xml version="1.0" encoding="UTF-8"?>

<Skills_I_Learn>

	<Skill1>Базовая теория (Что такое тестирование,документация,техники тест дизайна,виды тестирования и т.д.)</Skill1>
  
	<Skill2>Клиент-серверная архитектрура</Skill2>
  
	<Skill3>Статус коды ответов HTTP сервера</Skill3>
  
	<Skill4>HTTP методы запросов на сервер</Skill4>
  
	<Skill5>Структуры HTTP запросов и ответов</Skill5>
  
	<Skill6>Что такое JSON,XML.Их структура</Skill6>
  
	<Skill7>Тестирование API через Postman</Skill7>
  
	<Skill8>Снятие и чтение логов с внешнего сервера</Skill8>
  
	<Skill9>Снифинг http web трафика через Charles и Fiddler</Skill9>
  
	<Skill10>Dev Tools веб браузеров (Google Chrome,FireFox)</Skill10>
  
	<Skill11>Мобильное тестирование</Skill11>
  
	<Skill12>Особенность iOS,Android,гайдлайны</Skill12>
  
	<Skill13>Сборка Android приложений на Android Studio</Skill13>
  
	<Skill14>ADB(Управление андройд девайсами)</Skill14>
  
	<Skill15>Настройка прокси и vpn на ios и Android</Skill15>
  
	<Skill16>Перехват(сниффинг) мобильного трафика через Charles и Fiddler на ios и android</Skill16>
  
	<Skill17>Командная строка (terminal) Linux(копирование,создание,просмотр,перемещение файлов на серверах без графического интерфейса)</Skill17>
  
	<Skill18>Основы bash скриптинг,автоматизация рутинных задач на сервере</Skill18>
  
	<Skill19>Доступ к удалённым серверам</Skill19>
  
	<Skill20>Основы SQL (Create,Delete,Drop,Insert Into,Select,From,Where,Having,Join)</Skill20>
  
	<Skill21>База данных Postgres(установка,настройка и использование)</Skill21>
  
	<Skill22>Нагрузочное тестирование в Jmeter</Skill22>
  
	<Skill23>Методология разработки Scrum</Skill23>
  
	<Skill24>Python(Основы)</Skill24>
  
</Skills_I_Learn>

 32. Сделать коммит в одну строку.

git add.&&git commit -m "add skills and preferences"

 33. Отправить сразу 2 файла на внешний репозиторий.

git push

 34. На веб интерфейсе создать файл bug_report.xml.

Add file ==> Create new file ==> Name: bug_report.xml

<?xml version="1.0" encoding="utf-8"?>

<bug_report_structure>

    <summary>краткое описание</summary>
    
    <project>проект</project>
    
    <Environment>окружение</Environment>
    
    <ID>id</ID>
    
    <component>компонент приложения,модуль</component>
    
    <version>номер версии</version>
    
    <severity>серьезность</severity>
    
    <priority>приоритет</priority>
    
    <steps_to_reproduce>шаги воспроизведения</steps_to_reproduce>
    
    <Assigned_to>кому назначен</Assigned to>
    
    <actual_result>фактический результат</actual_result>
    
    <expected_result>ожидаемый результат</expected_result>
    
    <additional_information>дополнения</additional_information>
    
</bug_report_structure>

 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Press "Commit changes"

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

Choose bug_report.xml --> Edit this file

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Press "Commit changes"

 38. Синхронизировать внешний и локальный репозиторий XML
git pull

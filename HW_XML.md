## HomeWork XML


| Задание                                         | Решение          |
| ------------------------------------------------|:-----------------|
|  1)Создать внешний репозиторий c названием XML | github repositories new
|  2)Клонировать репозиторий XML на локальный компьютер| git clone https://github.com/Viktoriiazezul/XML.git               
|  3) Внутри локального XML создать файл “new.xml” | cat >new.xml |                 
|  4)Добавить файл под гит                       | git add new.xml |
|  5)Закоммитить файл                       | git commit -m new.xml|
|  6)Отправить файл на внешний GitHub репозиторий | git push |
|  7)Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате xml.
## 
```
cat >>new.xml
<My_name:Zezul_Viktoriia_Ivanivna>
<28_years>
<not_animals_home>
<desired Salary>:<1000 usd> 
```
ctrl+C

   8)Отправить изменения на внешний репозиторий git commit -m new.xml
                                                git push

   9)Создать файл preferences.xml   
   10)В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате xml. cat >preferences.xml
## 
```   
cat >preferences.xml
<film>:<Soul>
<serial>:<home on happy>
<eat>:<borsch>
<season>:summer
<cauntry>:<USA>
```
ctrl+C

  11)Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате xml.
  ## 
```  
cat >skills.xml
<those_course>:
<git>
<mobile_testing>
<SQL>
<python>
<web_testing>
```
ctrl+C

  12)Отправить сразу 2 файла на внешний репозиторий. 
  ## 
```  
git add .  
git commit -m preferences.xml 
git commit -m skills.xml
git push
```

  13)На веб интерфейсе создать файл bug_report.xml.
   ## 
``` 
add file
create new file
name your file
``` 

  14)Сделать Commit changes (сохранить) изменения на веб интерфейсе.
## 
``` 
update comment bug_report.xml
```
  
  15)На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате xml.
``` 
edit this file   
 ```  
 ``` 
submit new issue
  ```
  
 16)Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 update comment bug_report.xml
  ```
 17)Синхронизировать внешний и локальный репозиторий XML
 ```  
git clone https://github.com/Viktoriiazezul/XML.git
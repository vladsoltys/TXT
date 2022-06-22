# TXT

1. Создать внешний репозиторий c названием TXT.
>    Go to home page --> click on the button "New"(on the upper left) --> enter name "TXT" --> at the bottom click "Create repository"    
2. Клонировать репозиторий TXT на локальный компьютер. 
>    git clone https://github.com/vladsoltys/TXT.git
3. Внутри локального TXT создать файл “new.txt”. 
>    touch new.txt
4. Добавить файл под гит.
>    git add .
5. Закоммитить файл. 
>    git commit -m "add new txt file"
6. Отправить файл на внешний GitHub репозиторий. 
>    git push
7. Отредактировать содержание файла “new.txt” - написать информацию о себе 
     (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). 
     Всё написать в формате TXT. 
>    1)vim new.txt  
>    2)i
     
       Full name - Soltys Vladyslav Igorevich
       Age - 24
       Number of pets - 2
       Future desired salary - 800-1000$
                                                                                
>    3)esc :wq

 8. Отправить изменения на внешний репозиторий. == 1) git commit -am "change file new.txt"
                                                   2) git push

 9. Создать файл preferences.txt .............. == vim preferences.txt
 10. В файл preferences.txt добавить информацию о своих предпочтениях 
     (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) 
     в формате txt. ............................................ == 1) i(insert)
        Favourite film - Contact
        Favourite series - Breaking Bad
        Favorite food - Mother's potato pancakes with cheese
        Favorite time of year - Summer
        Country you would like to visit - Cuba
                                                                    2)esc :wq

 11. Создать файл skills.txt,
     добавить информацию о скиллах которые будут изучены на курсе в формате TXT ==
     1) vim skills.txt
     2) i
        Skills to be learned on the course:
        1) Basic theory (What is testing, bug reports, documentation, types, methods, testing directions, etc.) SDLC, STLC
        2) What is a client-server architecture
        3) HTTP Methods of requests to the server
        4) HTTP server response codes
        5) Structures of HTTP requests and responses
        6) What is JSON, XML. Their structure
        7) API testing via Postman (JS, API autotests)
        8) Removing and reading logs from an external server
        9) Sniffing http web traffic via Charles and Fiddler
        10) Dev Tools of web browsers (Google Chrome, FireFox)
        11) VPN. (How it works, why you need it, how to use it, tool options) 
        12) Mobile testing
        13) Feature iOS, Android, guidelines
        14) Building iOS applications on XCode
        15) Building Android applications on Android Studio
        16) ADB (android device management)
        17) Setting up proxy and vpn on iOS and Android
        18) Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android
        19) Command line (terminal) Linux (copying, creating, viewing, moving files on servers without a graphical interface)
        20) Basics of bash scripting, automation of routine tasks on the server
        21) Access to remote servers
        22) SQL basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)
        23) Postgres database (installation, configuration and use)
        24) Non-relational database Redis (installation, configuration and use) 
        25) Load testing in Jmeter
        26) Scrum development methodology
        27) Python. (Learning the basics. Creating a client-server application)
      3) esc :wq
     
 12. Сделать коммит в одну строку. ................. == git add . ; git commit -m "add 2 new txt files"
 13. Отправить сразу 2 файла на внешний репозиторий. == git push
 14. На веб интерфейсе создать файл bug_report.txt. == 1) click on the button "add file" 
                                                       2) click on the button "create new file" 
                                                       3) in the field "Name your file..." enter the name of the file "bug_report.txt"

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. == at the bottom click "Commite new file"
 16. На веб интерфейсе модифицировать файл bug_report.txt, 
     добавить баг репорт в формате TXT. == ........................... == 1) click on file "bug_report.txt"
                                                                          2) click on the button "Edit this file" in the lower right
                                                                          3) copy description of the bug
        Bug_id: 26
        Summary: "Loggin Page. The button 'Sigh in' not responding after clicking on it"
        STR:
            1) Open the login page
            2) Enter username and password
            3) Click on the button "Sigh in"
        Result: "The button 'Sigh in' not responding after clicking on it"
        Expected result: "After clicking the button, the user page opens"
        Severity: Major
        Priority: High
        Enviroment:
            OS: Windows 10 Pro.64-разрядная операционная система, процессор x64
            Browser: Google Chrome v.98.0.4758.102 (Розробка) (64-розрядна версія)


 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. == at the bottom click "Commite new file"
 18. Синхронизировать внешний и локальный репозиторий TXT == git pull

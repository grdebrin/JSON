# JSON
Homework GIT 1

 1. Создать внешний репозиторий c названием JSON.
 2. Клонировать репозиторий JSON на локальный компьютер. 
      
        git clone git@github.com:grdebrin/JSON.git
 3. Внутри локального JSON создать файл “new.json”. 
 
        touch new.json
 4. Добавить файл под гит. 
 
        git add new.json
 5. Закоммитить файл. 
 
        git commit -m "create new.json"
 6. Отправить файл на внешний GitHub репозиторий.  
 
        git push
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON. 
 
        nano new.json (открываем текстовый редактор nano и редактируем)
 8. Отправить изменения на внешний репозиторий. 
 
        git add new.json
        git commit -m "edit new.json"
        git push
 9. Создать файл preferences.json 
 
        touch preferences.json 
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON. 
 
         nano preferences.json (открываем текстовый редактор nano и редактируем)
 
 11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.
 
         touch skills.json
         nano skills.json 
 12. Отправить сразу 2 файла на внешний репозиторий.
   
         git add .
         git commit -m "add preferences.json and skills.json"
         git push
 13. На веб интерфейсе создать файл bug_report.json.
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 17. Синхронизировать внешний и локальный репозиторий JSON.
 
         git pull

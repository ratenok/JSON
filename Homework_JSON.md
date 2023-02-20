
### Homework JSON

|Задание |            Решение |
|------------- |------------- 
|Создать внешний репозиторий c названием JSON |`Create a new repository` (Repository name - JSON, Public, Add a README file -> Create repository)|
| Клонировать репозиторий JSON на локальный компьютер | `git clone` [https://github.com/ratenok/JSON.git](https://github.com/ratenok/JSON.git) |
|Внутри локального JSON создать файл “new.json” | `cd JSON` -перейти в папку JSON `touch new.json` - создать файл "new.json"|
|Добавить файл под гит | `git add new.json` |
|Закоммитить файл |`git commit -m "add new.json file"`|
|Отправить файл на внешний GitHub репозиторий | `git push`|
|Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON | `cat >>new.json` -> внести необходимую информацию -> `enter` -> `ctr+C` |
|Отправить изменения на внешний репозиторий | `git status` `git add new.json` `git commit -m "update new.json file"` `git push` |
|Создать файл preferences.json| `touch preferences.json` |
|В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON | `cat >> preferences.json` -> внести необходимую информацию -> `enter` -> `ctr+C` |
|Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON | `cat > skills.json` -> внести необходимую информацию -> `enter` -> `ctr+C` |
|Отправить сразу 2 файла на внешний репозиторий | `git status` `git add preferences.json skills.json` `git commit -m "add files"`| `git push` |
|На веб интерфейсе создать файл bug_report.json | `Add file` -> `create new file` -> ввести название bug_report.json |
|Сделать Commit changes (сохранить) изменения на веб интерфейсе | `Commit new file` |
|На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON | нажать на кнопку `Edit file` -> отредактировать
|Сделать Commit changes (сохранить) изменения на веб интерфейсе | отредактировав файл, нажать на кнопку `Commit changes` |
| Синхронизировать внешний и локальный репозиторий JSON | `git pull` |

# GitCommands

- clear
- cd <project dir>
- ls -a //to shaw hidden files
- git init
- git status
- echo "# Project Name" >> README.md
- git add README.md
- git add . //to add all files
- git commit -m "some text"
- git log
- git branch <new branch name> //to create
- git checkout <new branch name> 
- git checkout -b <new branch name> //to create + checkout
- git branch -d <branch name> //to delete
- git branch -m newName // to rename
- git merge <another branch name>
- git remote add origin https://github.com/id2k1149/<MyProjectName>.git
- git push -u origin main //to push local files to main remote github
- git restore <file>  
- git pull //to pull files from remote github to local git
- git mergetool //to solve merge conflict

- help.github.com
- learngitbranching.js.org

https://techrocks.ru/2019/12/02/writing-good-commit-messages
1. Указывайте тип коммита:

- feat: новая фича, добавляемая к приложению.
- fix: исправление бага.
- style: функции и обновления, имеющие отношение к стилизации.
- refactor: рефакторинг определенного участка кодовой базы.
- test: все, что касается тестирования.
- docs: все, что касается документации.
- chore: обычная поддержка кода, рутина.

# commands in Git

*Start*
For starting git you need open in cmd directory with file and initialized it: C\Users\Roman\Pycharm\gittest $ git 
init

For check status of files you must write in cmd command: $ git status
In this command you may see what files are modified, untracked, ready to commit

*Add*
For file's state will change from 'untracked' to 'ready for commit' you can use: $ git add file_name 

*Delete*
If you want to delete file in Git and it has not commited, you may use next command: $ git rm --cached file_name
After this command your file will stay in state 'untracked files'

*Commit*
Final stage, for saving your patch between 2 files, you need use command: $ git commit -m 'comment of commit'

*Ignore files*
If you want file not displayed in git, you should create a new file named '.gitignore' and write in this file all 
files what you want. After that added .gitignore in 'stage' (command add)
For ignore package you need to write in .gitignore '/package_name'



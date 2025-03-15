# Git-commands
Basic git commands :-
___________________________________________________________________________________________________________________________________________________________________________________________________________________
<br>
# ------------------------ Git Bash in use below commands ------------------------- <br>
1. git config -–global user.name “Your Name”   }==>   git config -–global user.name “Bashu-notes” <br>
2. git config –-global user.email “Your email”   }==>   git config -–global user.email “demo@gmail.com” <br>
3. git config --list   }==>   it's provide your name ,emial and (credential.helper=manager) list. <br>
<br>
# ----------------------- Now, use vs code edtior commands in terminal ------------------------- <br>
4. git --version     }==>  this is use for check git version. <br>
5. clear             }==>  this is use for clear terminal <br>
6. git clone Https-link   }==> (https-link) is your repostry link which you are clone on your local code editor. example:- git clone https:github.com/repostry <br>
7. cd foler-name               }==>  this is use for change directory ( means change folder ). example:- cd git-course <br>
8. ls                }==>  this is list file. it is use for check files in folder. <br>
9. ls -a             }==>  this command is use for check hidden files in folder. this is provide .git folder which is hidden. <br>
10. git status        ]==>  this is help to check status of your clone repostry menas:- ( On github repostry content is similar to local clone file. ) <br>
<br>
# -------------- git status type --------------- <br>
1. untracked:- Your are create a new file in local code editor but this is not preset on github <br>
2. modified:- Your are change text or add more text in code editor but not add on github through ( git add . ) command.<br>
3. staged:- You are add file through (git add .) command but not do commit. <br>
4. unmodified:- not change or not add something in file. <br>
<br>
11. git add file-name :- this is use for add file on github but not show in repostry. after that  use git commit command.<br>
12. git add . :- this is ude for add all files and all change in one time. <br>
13. git commit -m "meaage" :- this use for ready to push on github. basicaly local code is 1 step a head of remote(Github). example:- git commit -m "new-text add." <br>
14. git push origin main :- finaly my new work push on github. now on github show my new work. main is branch. first time show vs code authorized verification. <br>
15. cd .. :- this is use for outside of folder. <br>
16. mkdir folder-name :- this use for create new folder. example:- mkdir css-course. <br>
17. git init :- it is use for make git repostry to new folder. <br>
18. git remote add orgin link :- it is use for link repostry which are create in github without "README.md" file. orgin is branch name. example:- git remote add orgin https/github/newfile-js <br>
19. git remote -v :- it is use for verify to connect correct repo which are crete. <br>
20. git branch :- it is use for check currect branch in which you are work. by default branch is "main". old name is "master". <br>
21. git branch -M new-name :-it is use for rename the name of branch. example:- git branch -M master <br>
22. git push origin master :- it is use for create or rename branch to puch on github. <br>
23. git push -u origin master :- it is use for short cut for push code on github for long time work on master branch. after that create "README.md" file in local code. next use git add . and git commit -m mms. and last push the code sue of git push command. <br>
<br>
# ------------- Easy work flow of conect github repo to VS-Code edtior ----------------------- <br>
1. create repo on github. <br>
2. clone repo on local vs-code edtior with git clone command. <br>
3. add , cahange, edit and update content in connected repo file. <br>
4. add work through "git add ." command. <br>
5. next use "git commit -m message" command. <br>
6. last is push code or work on github through "git push origin main" command. <br>
<br>
24 cd .. :- it is use for exit to current folder or directory. <br>
25. git checkout -b new-branch :- it is use for create new branch. example:- git checkout -b custom <br>
26. git checkout branch-name :- it is use for change branch to move another branch. example:- git checkout main <br>
27. git branch -d branch-name :- it is use for delete branch. make sure not write branch-name which are you currently working so, show error. example:- git branch -d custom <br>
28. git push origin custom :- Now this command push code on custom branch. so write brnach name which are working ( carefull ). <br>
29. git diff comp-branch-name :- it use for comapre what differance current branch vs to another branch. example:- git diff custom <br>
<br>
# --------------- Me+rge the branches are to way 1. "git merge branch-name" command and 2. create PR with pull request ------------------------- <br>
30. I have use pull request method. it is perfom on github in which repo currently work. <br>
31. git pull origin main :- it is use fetch updated from remote (Github) to loacl vs-code editor like:- Now merge content in both branch. <br>
32. git pull origin cutom :- also it is use for fetch the data from github custom branch to local system. <br>
33. git merge branch-main :- it is use for merge the current work branch to specific branch like main. it is second method and perfom on local editor.  :- git merge main <br>
34. git merge custom :- it is also merge the code on custom name branch. after that push code to remote through "git push origin main" command<br>
<br>
# ---------------- For undo means Back to the step. this is apply on three stages ------------------ <br>
35. git reset :- it use for when i have delete and add the content. run the "git add ." command , but I want previous content. it's first stage. <br>
36. git reset HEAD~1 :- it use when run the "git commit" comand. but you need reset so use this command. HEAD is last change step. <br>
37. git log:- it's provide steps whcih are currenty use. It also call hesh # values. <br>
38. git reset --hard :- it use for hard reset then show the previous data. <br>


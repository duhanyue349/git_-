# git_-
git clone https://github.com/JayceNing/AI_study_notes.git

[user]
email=duhanyue349@163.com
name=duhanyue349

git init
git add *
git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/duhanyue349/AI_-.git

git push -u origin main

一、出错信息：fatal: remote origin already exists.

解决方法：
1、先删除远程 Git 仓库
$ git remote rm origin
2、再添加远程 Git 仓库

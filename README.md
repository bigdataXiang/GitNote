#如何将本地项目远程同步到github
+ 1、File->New->Project 建立新项目
+ 2、建立".gitignore"文件
+ 3、建立"pom.xml"maven配置文件
+ 4、在github建立与项目名称相同的仓库，获得其url
   "https://github.com/bigdataXiang/GitNote.git"
+ 5、在终端执行以下命令：
```
   git init
   git add -A
   git commit -m "~"
   git remote add origin https://github.com/bigdataXiang/GitNote.git
   git push -u origin master
```  

#git命令的含义
[常用git命令](http://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html)
git push -u origin master # 客户端首次提交

git push -u origin develop # 首次将本地develop分支提交到远程develop分支，并且track

git push # push所有分支

git add . # 将所有修改过的工作文件提交暂存区

git help <command> # 显示command的help

git show # 显示某次提交的内容 git show $id

git pull # 抓取远程仓库所有分支更新并合并到本地

git init # 在当前目录新建一个Git代码库
 
git init [project-name] #新建一个目录，将其初始化为Git代码库

git clone [url] #下载一个项目和它的整个代码历史

git config： http://blog.csdn.net/wirelessqa/article/details/8572928
#如何将本地项目远程同步到github
1、File->New->Project 建立新项目
2、建立".gitignore"文件
3、建立"pom.xml"maven配置文件
4、在github建立与项目名称相同的仓库，获得其url
   "https://github.com/bigdataXiang/GitNote.git"
5、File->New->Project from Version Control->git/github
   将远程项目同步克隆到本地
6、在终端执行以下命令：
   git add -A
   git commit -m "~"
   

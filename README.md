这是测试docker的openapi 和远程git控制系统
用vsc 连接阿里云服务器
用git 实行版本控制
用docker 进行python开发
学习git 看廖雪峰教程，很清晰
git 跟踪并管理的是修改,而不是文件
现在远程建立一个repository,设置public
在本地 git remote命令: git remote add origin git@github.com:freshapex/testapi.git
然后push命令： git push -u origin master   #这是把本地库的内容推送到远程，用git push命令，实际上是把当前分支master推送到远程.远程库的名字就是origin，这是Git默认的叫法，也可以改成别的，但是origin这个名字一看就知道是远程库。
由于远程库是空的，我们第一次推送master分支时，加上了-u参数，Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来，在以后的推送或者拉取时就可以简化命令。
从现在起，只要本地作了提交，就可以通过命令：git push origin master
